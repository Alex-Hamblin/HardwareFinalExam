# HardwareFinalExam


# Part 1

1.
<img width="485" height="326" alt="image" src="https://github.com/user-attachments/assets/4b7f635e-584b-4efd-870f-87bcb777ddfd" />



2. 
V = 2 * 20 = 40
P = 40 * 20 = 800
The resistor you will need to use is the 150 Ohm resistor. 

# Part 2

# Brainstorming Process
The game i am creating a controller for is PunchOut!!
the controller will need inputs for each of the directions you can dodge in, and inputs for each of the directions you can attack in. 

The controller i wish to create is similar to a WII remote, with multiple buttons used as digital input and an accelerometer to detect when the player performs a certain motion with the contoller. Because we are using the accelerometer, we can detect motion inputs for when the player wants to attack, each direction can be labeled as a different attack. this will add more immersion to the gameplay and also free up space on the controller as you need less button inputs. 



# Electronics Prototype TinkerCAD
As tinkerCAD does not have an accellerometer in its inputs, i will be using a flex sensor in its place. 

I have used 2 push buttons for dodging and blocking, each with a corresponding LED to show that the input was registered, and a flex sensor with an LED to register that an attack was made. 

I have added a vibration motor that plays when an attack is performed, this lets the player know that their input was registered without having to put extra LEDs
<img width="642" height="322" alt="image" src="https://github.com/user-attachments/assets/c2318800-d2df-4570-a50d-2cde5be5bb9e" />




https://github.com/user-attachments/assets/8eebdb9a-3c32-4911-a82f-86ba6fbb6117



<img width="338" height="326" alt="image" src="https://github.com/user-attachments/assets/14fb41f3-d1ce-4919-a0d7-afdf4d15be23" />


List of components:

<img width="911" height="328" alt="image" src="https://github.com/user-attachments/assets/696ad186-2864-4255-ad6c-fcf952d4d796" />


# CAD Prototype
When designing the prototype, i wanted a shape that felt good to hold in the hand, sturdy enough to swing around, and immersive enough to feel like you were actually punching in the game. That i why i went for a more vertical rectangular shape, as proven by the WII remote, the shape is comfortable to hold and swing around. 
<img width="681" height="290" alt="image" src="https://github.com/user-attachments/assets/19943fa9-e1c3-49f2-8535-fe20bcd8723d" />

I have added 2 holes on the top for the buttons to register player inputs, and 2 smaller holes above that that will fit the LED's to show that the input is being played.

When i was trying to create the schematics for the electrical components in KiCAD, i was having issues with them not correctly appearing within the PCB editor, causing me to have to design the controller without being able to view the board. So the shape and design of the controller is designed around the ideal position of all of the components. 
<img width="605" height="336" alt="image" src="https://github.com/user-attachments/assets/524cbe80-fe09-43be-b49a-69c6f27719e8" /> 
When generating the design based off of the sketch, it only generated the connection between the Acclerometer and the Arduino, and did not generate the rest of the components. 

# bill of materials 
<img width="923" height="329" alt="image" src="https://github.com/user-attachments/assets/72b4ff9b-d162-4cb0-a230-91959ffa0b30" />  

# Technical Drawings
<img width="416" height="293" alt="image" src="https://github.com/user-attachments/assets/940024f5-f713-4b7f-9207-ca408c9132ed" />


