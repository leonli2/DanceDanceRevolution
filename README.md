# Dance Dance Revolution
Co-developed a playable Dance Dance Revolution on CPUlator, a website that simulates the DE1-SoC board.

# Note
Since this is a project for Computer Organization at the University of Toronto, the source code cannot be shared due to Academic Integrity reasons.

# Video
https://user-images.githubusercontent.com/112602959/196615952-22649e22-45fd-4ec8-9f48-6f5f5dee81f8.mp4

# Background
• Randomly generated arrows with fixed speed will fly upwards across the screen.<br/>
• Once they match the arrow outline at the top of the screen, the player should press the corresponding key.<br/>
• The objective is for the player to score as much points as they can in 60 seconds.<br/>
• There is also a combo tracker, which increases by 1 everytime the player sucessfully hits the correct arrow with the correcting timing.<br/>
• This combo multiplies the points they get from subsequent arrows.<br/>
• Reaching a combo of 15 will give a x2 multiplier, while a combo of 30 will give a x3 multiplier.

• There are 4 accuracy types depending on how close the player was to pressing the arrow key at the correct time (WOW, GOOD, OKAY, MISS).
  1. WOW means perfectly aligned or very close.
  2. GOOD means somewhat close.
  3. OKAY means touching the arrow outline.
  4. MISS means that the player either let the arrow hit the top or pressed the wrong key.<br/>

• These give 3, 2, 1, and 0 points respectively.<br/>
(Note: a MISS also resets the combo to 0)

# How to Play
• First, press KEY0 in order to start the game.<br/>
• This will then start a countdown, after which the game begins.<br/>
• Once the keys overlap their outline, the player should press the corresponding key.<br/>
• To score more points, they should try to get a combo by avoiding a MISS.<br/>
• After 60 seconds, the game is finished.
