# Robot Arm Plan

#### Goal
- Construct an arduino-controlled robot arm from materials in the sigma lab.

#### Resources/Materials
- 4-6 servos
- Arduino
- 9V battery pack
- Gears made out of 3mm acrylic
- 5 mm LEDs
- Switch (for power)
- Potentiometers (for controlling servos) 
- Photo interrupters
- 3D printer and laser cutter

#### Schedule
- *Before winter break*
  - Finish brainstorming and submit detailed plan
- *After winter break ~ solidworks*
  1. Make the base of the arm
     - Box connected by corner tabs
     - Properly dimensioned holes for screws, arduino, led, switch, potentiometers
      - Hinge for one side of the box
  2. Make the strips of acrylic connected by gears
     - These should be relatively simple pieces, they are just put in place to increase the distance between the “joints”       of the assembly
      - They will just have holes to connect them to the other pieces
      - Serve no other significant function
  3. Make the “claw” that picks up the object
     - Each side has gears on one side, when they are connected it makes the claws open and close together when only one         of them is being controlled by the servo
      - The other side has “teeth”
     - The ridges make it less slippery and less likely to drop the object
  4. Make the servo holders 
      - Material surrounding the base of the servo and connects to the acrylic
  5. 3D print holders, laser cut all pieces
  6. Assemble! 



- *After winter break ~ wiring/code*
  1. Power switch to led and battery
      - Switch should turn on the entire thing, and the led should indicate when it is on
  2. Photo interrupters
  3. Potentiometers
  4. Servos
  
  - All of the wiring and code is fairly straightforward
  - Some difficulties may include
    - Figuring out how to fit all of the wiring onto one arduino and maximize space
    - Making sure the potentiometer is set up to move the servo in the correct direction 


#### Ideas
- Each servo corresponds to the moving parts of the arm (left/right, up/down, open/close)
 - Potentiometers on the base of the arm will control each direction
- Labels will be printed to indicate what servo it corresponds to
- The base of the arm is just a box, containing the arduino and battery pack
- One side of the box will be able to open with a hinge/knob, in order to allow easy access if the wiring or batteries    had to be changed
- It will use continuous rotation servos, but will the range will be limited by a photo interrupter so the moving parts don’t hit other parts of the arm
- Approximate size of box: length = 150 mm, width = 100 mm, height = 80 mm

