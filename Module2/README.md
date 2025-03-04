# Module 2 (week 2 & 3)

## week 2
- My kit contains: \
    ![My kit photo](../Module1/Pictures/02-kit_upper.jpg) \
    Red packet: 3 LED, 1 capacitor, 4 resistors, 2 swtichers \
    1 AC/DC adaptor \
    1 breadboard \
    5 jumper wires \
    1 relay shield \
    1 ESP8266MOD \
    1 mh-kc24-4 \
    1 lock \

- What is a breadboard for electronic prototyping? Describe a breadboard, include at least 2 remarkable/memorable features
  * So this a grid platform where you can quickly build electronical circuits. Ideal thing for learning / experimenting.
  1. it has solderless design. Easily put or remove components.
  2. some internal connectivity. It has metal strips that creates connections
- Name one (or two) convention(s) for color coding for cables
  * I know that usually *black* cable for ground(-), red cable for positive(+).
- How do you a wire a Light Emitting Diode (LED) to 5V? Describe an LED, what is special about (light-emitting) diodes?
  * We need resistor, LED, and power source. 
  * LED is a device that emits light. LED by itself has anode(+) and cathode(-). The first one usually longer than the latter.
  1. It has only one way connection from + to -
  2. Doesn't produce heat because there is a process called electroluminescence.


- Why esp8266?
  * Because they are very good in terms of price and quality
- What is personally inspiring for you?
  * That I actualy can build something valuable for that low price
- What is the connection to coffee?
  * It costs as cheap as a cup of coffee, but it's more valuable



- lookup 1 other MCU online
  * The Arduino Uno is a widely-used microcontroller board based on the ATmega328P microcontroller. It features 14 digital input/output pins, 6 analog inputs, and operates at a 5V logic level.
- note 2 (dis)advantages of the Wemos D1 Mini vs other MCUs, note down 1 way this might impact your work
  Advantages:
  1. Unlike many traditional MCUs, the WeMos D1 Mini comes with built-in Wi-Fi capabilities
  2. Its small size makes it ideal for projects with space constraints
  Disadvantages:
  1. The WeMos D1 Mini offers only one analog input pin
  2. Operating at 3.3V logic levels, it may pose compatibility challenges

  If your project involves multiple analog sensors, the single analog input of the WeMos D1 Mini could be a limitation

- Mini Project: LED-button \
![Calculations](../Module1/Pictures/02-calculations.jpg) \
![What we built](../Module1/Pictures/02-mini_project.jpg) \
![Connecting LEDs in parallel](../Module1/Pictures/02-parallel_connection.jpg) \
![Connecting LEDs in series](../Module1/Pictures/02-series_connection.jpg)


- Mini Project: Relay-Lock-Button \
![Relay before](../Module1/Pictures/02-relay_project.jpg) \
![Relay after](../Module1/Pictures/02-last_project.jpg)

- Normally open normally closed?
  It depends on where you connect cable. 
  1. If you plug cable into right socket then it's normally closed
  2. If you plug cable into left socket then it's normally open

## week 3

- I got kit to go: \
    ![My kit photo](../Module1/Pictures/02-kit_upper.jpg) \
    Red packet: 2 LED, 1 capacitor, 3 resistors, 2 swtichers \
    1 AC/DC adaptor \
    1 breadboard \
    9 jumper wires \
    1 relay shield \
    1 mh-kc24-4 \
    1 lock \
    1 ESP-12F \
    1 Sever motor \
    1 sensors \
    1 LED lent \
    1 USB \

- Low-Level Busses. \
   We took CAN(Control Area Network) 
  CAN is a vehicle bus standard used for communication between electronic control units (ECUs) in vehicles in order to reduce wiring complexity and cost
  * It can be used in Vehicles, Agricultural equipment, Industrial automation, Medical instruments
  * First used in the 1991 Mercedes-Benz W140
  * Gran Turismo 6 (videogame): used to recreate real-life racing laps
  * Has only two wires: CAN High (dominant) and CAN Low (recessive).
  * Speed: 1.0 Mbit/s, up to 5.0 Mbit/s for CAN-FD.
  * Special properties: Multi-master, priority-based arbitration, error detection & correction, differential signaling (noise immunity).

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
  
  Photos from the first mini project: \
  ![Lights_on](../Module2/Pictures/01-lights_on.jpg) \
  ![Lights_off](../Module2/Pictures/01-lights_off.jpg) \
  ![Code](../Module2/Pictures/01-code.jpg)

  Photos from smooth light on and off: \
  ![Lights_on](../Module2/Pictures/02-lightson.jpg) \
  ![Lights_off](../Module2/Pictures/02-lightsoff.jpg) \
  ![Code](../Module2/Pictures/02-code.jpg) \
  [Video](../Module2/Pictures/02-video.mp4)
  
- Which IDE do you prefer working with? Why?
  I use VSCode (it is not an IDE) everywhere where it fits. It is lightweight, functional, easy to setup, easy to make IDE from text redactor.

- Photos from mpr121 mini project: \
  Lime test: \
  ![Lime test](../Module2/Pictures/mpr121-lemon.jpg) \
  ![Lime test output](../Module2/Pictures/mpr121-lemon-out.jpg) \
  Water test: \
  ![Water test](../Module2/Pictures/mpr121-water.jpg) \
  ![Water test output](../Module2/Pictures/mpr121-water-out.jpg) \
  Metal test: \
  ![Metal test](../Module2/Pictures/mpr121-metal.jpg) \
  ![Metal test output](../Module2/Pictures/mpr121-metal-out.jpg) \
  Program code: \
  ![MPR121 code](../Module2/Pictures/mpr121-code.jpg)


## Reflections
[Reflection 2](../Reflections/ref02.md) \
[Reflection 3](../Reflections/ref03.md)