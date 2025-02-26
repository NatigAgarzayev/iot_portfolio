# Reflection 3 in Module 2

- What is your take-away, what do you want to remember, what would be your advice?
  It's was really interesting programming devices. Make less mini projects because we usually don't have time to complete them in active class. 
- What was good?
  Team work. 
- What was difficult, where did you struggle?
  I was hard to setup platform io because I did dumb mistake (I did not plug the usb to the laptop)
- Was there any good/fun “struggling”/exploration?
  As I said when we found out about this with Fedir it was kinda funny
- How was your interaction with peers/instructors?
  Really good. I enjoyed that.
- Help and extra work
  - Who helped you, gave feedback, was it valuable?
    Fedir helped me to connect breadboard to platform io. Also, one guy gave me serve motor. Unfortunatelly, I don't know his name, but 
  - Who did you help, gave feedback to? 
    I helped Anna Sulg to fix problem with breadboard during one of the mini projects.
  - Did you present, implement, made a PR, or fix something that was crucial for the class in itself?
    So far so good.

- I got kit to go:
    [My kit photo](../Module1/Pictures/02-kit_upper.jpg)
    Red packet: 2 LED, 1 capacitor, 3 resistors, 2 swtichers
    1 AC/DC adaptor
    1 breadboard
    9 jumper wires
    1 relay shield
    1 mh-kc24-4
    1 lock
    1 ESP-12F
    1 Sever motor
    1 sensors
    1 LED lent
    1 USB

- Low-Level Busses.
  We took CAN(Control Area Network) 
  CAN is a vehicle bus standard used for communication between electronic control units (ECUs) in vehicles in order to reduce wiring complexity and cost
  It can be used in Vehicles, Agricultural equipment, Industrial automation, Medical instruments
  First used in the 1991 Mercedes-Benz W140
  Gran Turismo 6 (videogame): used to recreate real-life racing laps
  Has only two wires: CAN High (dominant) and CAN Low (recessive).
  Speed: 1.0 Mbit/s, up to 5.0 Mbit/s for CAN-FD.
  Special properties: Multi-master, priority-based arbitration, error detection & correction, differential signaling (noise immunity).

  Also You asked about 1 difference from Modbus.
  Modbus Protocol is a messaging structure, widely used to establish master-slave communication between intelligent devices.
  But CAN can establish connect with every device.

- Blink = Arduino Hello World
  1. How are programs saved and run on the Wemos D1 Mini – how many at once?
    Programs for the Wemos D1 Mini are saved in flash memory and run from there. Only one program runs at a time.
  2. Which voltages did you use? Which voltages can you use? 
    It operates on 3.3V logic, but you can power it via 5V (USB) or 3.3V (VCC pin).
  3. What means High and what means Low?
    High means 3.3V, and Low means 0V (GND).
  4. Where do you look easiest for examples for your solutions?
    The easiest place for examples is the Arduino IDE Examples, ESP8266 documentation, or community forums (like GitHub and Stack Overflow).
  5. What is special about the onboard led on the Wemos D1 Mini?
    The onboard LED is inverted, meaning LOW turns it on, and HIGH turns it off.
  
  Photos from the first mini project:
  [Lights_on](../Module2/Pictures/01-lights_on.jpg)
  [Lights_off](../Module2/Pictures/01-lights_off.jpg)
  [Code](../Module2/Pictures/01-code.jpg)

  Photos from smooth light on and off:
  [Lights_on](../Module2/Pictures/02-lightson.jpg)
  [Lights_off](../Module2/Pictures/02-lightsoff.jpg)
  [Code](../Module2/Pictures/02-code.jpg)
  [Video](../Module2/Pictures/02-video.mp4)
  
- Which IDE do you prefer working with? Why?
  I use VSCode (it is not an IDE) everywhere where it fits. It is lightweight, functional, easy to setup, easy to make IDE from text redactor.