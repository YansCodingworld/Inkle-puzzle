# Inkle-puzzle
Ink game
Save Your Family From Zombie Zone

-> start
===start
You wake up alone at home. Where is your family? What happened?
+[Watch the News] -> television

===television
The news is reporting a new zombie virus. You realize the world is undergoing a significant shift; the zombie virus swept the town. Your neighbors, family, and friends have all become zombies. It seems like you are the only one who has not been affected by the virus. You should seek ways to save the town!

-> room
===room
Is there anything useful you can find in your room? You can go outside as well.

+ Search the Room
   -> Search


+ [Go Outside]
You step in your car. There appear to be two directions: go right or left?
    ++[Go Left] -> Left
    ++[Go Right] -> Right
 
 -> Right
 === Right
     You notice a hospital down the street, but only one room with dim light. Do you want to go there to check what is going on there?
        + Yes 
            -> hospital

        + No
        ->room

-> Left
 === Left
    The town is in a mess. People ran around because a zombie may bite them at any time. Without the constraints of the rules, the world is under a scene of doomsday. 
   
   However, you see a surviving person standing on the corner of this road. 
    
    +[Who is he?] -> Check
    
    ===Check
    That is a policeman, covered by protective suits. Go ask him for help!
    +[Ask the policeman for help] -> Help
        === Help
        "Hello, Sir, could you save my family? They are all infected by the zombies." You asked desperately.
        "I don't know. You can turn right and go down to the street, where maybe someone in the hospital can help you." Said the police. 
        ++[Go to the Opposite Direction] -> Right
        
    -> hospital
    ===hospital
    Oh! This is a vast hospital. 
    "Anyone can help me out?" You screamed.
        No one responds, so you have to enter the scary hospital to check yourself.
        + [Enter the Hospital] -> Enter
        
        === Enter  
        + [Office A]
            Nobody is here. You go back to the main building. ->hospital
        + [Office B]
            Oops, the office is empty. You go back to the main building. ->hospital
        + [Office C]. 
            You see a tall man with white cloth. Who is he? 
            ++ [Speak to him] -> Speak
                === Speak
                "Excuse me, could you help my family. The zombie virus infects them." You spoke carefully.
                
                "You found the right person. I am Dr.Bass. I've been waiting for you for a long time." ->Success 

    -> Success

    ===Success

    Dr. Bass successfully invented the new vaccination for the zombie virus. He offered you the cure for the virus, too. You SUCCESSFULLY save your family. Congrats!
    -> END

 ->Search
 ===Search

    There is a closet. Check if there is something in it. Meanwhile, you hear a weird sound coming from the bottom of the bed. You can also start looking beneath the bed.
    
    + Check the Closet
        Woah! A wind of dust blows into your eyes, but there is nothing.
        ---Search the room again or go outside. -> room



    + Look Beneath the Bed
        Squeeking and hissing. A rat rushed, but there is nothing. You return back to the main room.
            ->room
