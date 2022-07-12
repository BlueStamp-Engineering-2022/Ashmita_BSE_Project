# Ring Lockbox
A box that will lock and unlock with a specific ring.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Ashmita A | Evergreen Valley Highschool | Computer Science | Incoming Sophmore

![Headstone Image](https://photos.google.com/share/AF1QipPfXXrUy84d3RworMUQWytms_AhB1PhceeMV76HeIOtnnEISkmCd99oGmAbPtCnKQ/photo/AF1QipNtGHE-_J-aHGGSM4qxV-BU0tkJFJSRBa1sXV7x?key=blBtb2RCb01sX1hWc04xS3NMREJ0d3FUOWY2eWxB)
  
# Final Milestone
My final milestone is the increased reliability and accuracy of my robot. I ameliorated the sagging and fixed the reliability of the finger. As discussed in my second milestone, the arm sags because of weight. I put in a block of wood at the base to hold up the upper arm; this has reverberating positive effects throughout the arm. I also realized that the forearm was getting disconnected from the elbow servo’s horn because of the weight stress on the joint. Now, I make sure to constantly tighten the screws at that joint. 

[![Final Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612573869/video_to_markdown/images/youtube--F7M7imOVGug-c05b58ac6eb4c4700831b2b3070cd403.jpg )](https://www.youtube.com/watch?v=F7M7imOVGug&feature=emb_logo "Final Milestone"){:target="_blank" rel="noopener"}

# Second Milestone
My second milestone is putting the Arduino, PN532, and servo into the front of the box. First I had to solder some wires to get the Arduino to work without beinig connected to the laptop. I also tried to get the lock mechanism to work, but no matter how hard I tried to make the servo move the lock, the servo could not do it. After realizing that my initial idea would not work, I had to rethink and I decided to use the servo as the main lock. I 3D-printed my own lock and coded the servo to work with the lock. I then ran into problems with the soldering as I forgot to add a wire and adding it after soldering the main ones made it loose. After getting all the wires together I started testing the Arduino to see if it worked without being connected to the computer. While that took some time I got it to work. The final step was gluing the servo in to make it lock.

[![Second milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1657380606/video_to_markdown/images/youtube--N2ovHtlDTGM-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=N2ovHtlDTGM "Second milestone")

# First Milestone
My first milestone was setting up the arduino, PN532, and servo to work with the code I set up. I wired it to connect them all the components. To start coding I had to download the right software for the arduino. I started by downloading the libraries necessary for the Pn532 to communicate with the Arduino and read the key and card. I first used some example code to see if the PN532 worked and that was where I ran into problems. It took around 40 minutes to fix that problem and the Pn532 started reading the key and tag. When I tried to read the NFC ring, the Pn532 refused to read it. After a couple of tries it read the ring, but the ring had to be touching the board which wouldn't be feasible when the board was in the box. So I decided to use the key with my project and started coding to verify the key. I also worked out how the servo worked as I needed to embed that in my code. At first the PN532 would read the key but kept saying that it was the wrong one. The problem was that there were unnecessary characters with the verification and I capitilized the actual characters. Once I got the verfication working, I moved the servo code into my verification code.

[![First Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1656872253/video_to_markdown/images/youtube--vi1xcE491zE-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=vi1xcE491zE "First Milestone")

# Starter Project
My starter project was the Useless Machine. I soldered the switch, resistors, screw terminal, LED, and scnap switch onto the Pc board. I then added the motor, arm and battery, I connected the wires to the PCB board. The switch sends an electrical current through the poles of the motor which then creates an electromagnetic field. That field will switch the poles which causes the axel to spin. The switching of the poles cause the motor to keep spinning. When I first connected the wires the motor didn't work as I had put the motor wires in the wrong spot. Even after fixing that mistake the motor still wouldn't spin. The problem was that the screw terminal was clipping on the insulation of the black wire of the battery and not on the wire itself. After fixing that  the motor started working smoothly. Putting the base together took up a lot of time as well as sore hands. The base was not coming together at all and I kept hurting myslf with the screwdriver. After twenty minutes of trying to self-thread the poles, I ended up asking my peers for suggestions and fixed the problem.

[![Starter project](https://res.cloudinary.com/marcomontalbano/image/upload/v1656717746/video_to_markdown/images/youtube--ZKi1Vb6d4pY-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=ZKi1Vb6d4pY "Starter project")
