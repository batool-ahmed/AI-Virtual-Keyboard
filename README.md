# AI Virtual Keyboard

This is a simple Virtual Keyboard:
- in QWERTY Format
- with alphabet keys (in uppercase) + special characters (; , .) + backspace key (b)
- using finger gestures and positions to hover, click and type text
- with a text bar to display text
- with the ability to also write on other open text apps or browser

# Language and Libraries:
- The Main Language used was Python
- The libraries and modules used were cvzone, open-cv, mediapipe, time, and pynput

## How to use this:
- You need a code editor, a Python Interpreter and a functioning camera on your pc
- Running main.py using the above two will display your virtual keyboard
- This will open up your real-time video with a keyboard on top of it.
- Hovering over a key with your index finger of any of your hands will highlight that key in a dark purple color.
- Closing the gap between your index and middle finger will turn the key green and will click it.
- The clicked key will be displayed in the purple rectangle below the keys layout.
- If you have any other writing app or a browser open then your clicked key will also be displayed there as text.
- To end the program, you will need to interrupt it by pressing ctrl+c on your pc keyboard

## Please note:
- Though at one time both of your hands will be recognized, yet only one of the hands' fingers will be taken as input.
- Specifically the hand being shown with purple joint points and a green enclosing will be taken as the input hand.

## Screenshots:
### Keyboard:
![Keyboard](https://github.com/batool-ahmed/AI-Virtual-Keyboard/blob/main/images/keyboard.PNG)
### Howering over a key:
![Hover](https://github.com/batool-ahmed/AI-Virtual-Keyboard/blob/main/images/hover.PNG)
### Clicking a key: 
![Click](https://github.com/batool-ahmed/AI-Virtual-Keyboard/blob/main/images/click.PNG)
### Backspace key:
![Backspace](https://github.com/batool-ahmed/AI-Virtual-Keyboard/blob/main/images/back-key.PNG)
### Textbox:
![Textbox](https://github.com/batool-ahmed/AI-Virtual-Keyboard/blob/main/images/text.PNG)
### Typing on Notepad Demo:
![Notepad Demo](https://github.com/batool-ahmed/AI-Virtual-Keyboard/blob/main/images/notepad-demo.gif)
<img src="https://github.com/Adnan-Asif/3D-Optimal-Path-Planinng-and-Compression/blob/main/imgs/car2_gif.gif" alt="Compressed Car" width="400" >

## Future Work:
- Ability to repeat a character consecutive
- Adjust time latency between clicks
- Add more characters and keys
- Add the ability to switch between lower and upper case
- Add a command to end the program
- Optimize the code
- Make its UI aesthetic
- Make it more User-friendly and adhesive to UX principles

## Inspiration:
This Project was inspired by 'Murtaza's Workshop - Robotics and AI''s video: https://www.youtube.com/c/MurtazasWorkshopRoboticsandAI

