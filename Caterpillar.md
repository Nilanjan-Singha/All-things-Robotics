#  Build Your Own Caterpillar Bot

---

##  What’s a Caterpillar Bot?

A **caterpillar bot** is a small tracked robot that moves like a tank or a bulldozer.  
Instead of wheels, it uses **track belts** wrapped around pulleys to crawl over rough or uneven surfaces.  
It’s great for:

- Learning the basics of **mechanical design + electronics**
- Navigating **off-road or uneven terrain**
- Experimenting with **autonomous robotics**

Think of it as your first step towards making a mini **Mars rover** or **search-and-rescue bot**.  

---

## 1. Gather Your Stuff

Before you start, make sure you’ve got everything:

- 1.0 – 1.5 mm **steel sheet** (or wood, but steel is stronger)
- **4 Johnson motors** (use 2 for drive, 2 dummies for balance)
- **4 motor clamps**
- Nuts & bolts (to fit the clamps)
- Screwdriver kit
- Soldering iron kit
- **4–6 XT60 connectors**
- **LiPo battery** (match your motor rating)
- Wires + wire cutter/stripper
- Black tape or heat-shrink
- Masking tape
- **4 pulley wheels** (same size)
- **2 track belts** (matching pulley size)
- Zip ties
- Sandpaper (for wheel grip)

---

## 2. Design Your Bot

- Sketch your bot or use AutoCAD/Fusion 360.
- A rectangular or “I” shaped base keeps it light but strong.
- Mark motor and clamp positions clearly.

---

## 3. Cut the Base

- Take your steel sheet to a **laser cutting/fabrication shop**.
- Cut the shape you designed.
- Drill **16 holes** (4 at each corner) for the motor clamps.
- Test a clamp with screws to make sure holes are right.

---

## 4. Mount the Clamps

- Bolt all four motor clamps to the base.
- Keep them **aligned**; misalignment makes belts slip.

---

## 5. Wire & Install the Motors

- Solder wires to the motor terminals.
- Cover joints with black tape or heat-shrink.
- Add an XT60 connector to each motor’s wires.
- Mount **two motors diagonally** (front-left + back-right) as drivers.
- Mount **two dummy motors** in the other diagonal for support/tension.

---

## 6. Add Pulley Wheels

- Lightly sand the pulley wheels for grip.
- Tighten them onto the motor shafts.
- Double-check both sides are lined up.

---

## 7. Fit the Track Belts

- Loop a track belt over the front and back pulley wheels on one side.
- Mark the length, trim off extra, and glue or stitch ends securely.
- Repeat for the other side.
- Make sure the tension is **equal on both belts**.

---

## 8. Test Your Bot

- Connect the LiPo battery.
- Make sure **both motors spin the same way**.
- Run at low speed first to check the belts stay on.
- If belts slip off:
  - Re-align the pulleys
  - Match motor speeds
  - Adjust belt tension

---

##  Done!

Your caterpillar bot is ready to roll!  
Test it on different surfaces and tweak belt tension or motor speed if needed.

---

###  Bonus Ideas

- Add an ESC (Electronic Speed Controller) for smoother control.
- Use a microcontroller (Arduino, ESP32, etc.) + motor driver to steer.
- Monitor your LiPo voltage to protect the battery.
- Add sensors for autonomous movement.
