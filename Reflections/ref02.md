# Reflection 2

- What is your take-away, what do you want to remember, what would be your advice?
  It's not so easy as I expected. At first I did not understand how elements interact with each other, but close to the end of the session it became more clear. 
- What was good?
  I asked questions and got clear explanation from instructor 
- What was difficult, where did you struggle?
  I was struggling while connecting leds in series. It was harder than parallel one.
- Was there any good/fun “struggling”/exploration?
  That I actually can connect elements without cable between them
- How was your interaction with peers/instructors?
  I was in a team with @anji5h. We did all practice tasks together.
- Help and extra work
  - Who helped you, gave feedback, was it valuable?
    Yes. Instructor explained unclear moments. 
  - Who did you help, gave feedback to? 
    I helped @anji5h to calculate resistor value.
  - Did you present, implement, made a PR, or fix something that was crucial for the class in itself?
    So far so good.

- My kit contains:
    [My kit photo](../Module1/Pictures/02-kit_upper.jpg)
    Red packet: 3 LED, 1 capacitor, 4 resistors, 2 swtichers
    1 AC/DC adaptor
    1 breadboard
    5 jumper wires
    1 relay shield
    1 ESP8266MOD
    1 mh-kc24-4
    1 lock

- What is a breadboard for electronic prototyping? Describe a breadboard, include at least 2 remarkable/memorable features
  So this a grid platform where you can quickly build electronical circuits. Ideal thing for learning / experimenting.
  1. it has solderless design. Easily put or remove components.
  2. some internal connectivity. It has metal strips that creates connections
- Name one (or two) convention(s) for color coding for cables
  I know that usually *black* cable for ground(-), red cable for positive(+).
- How do you a wire a Light Emitting Diode (LED) to 5V? Describe an LED, what is special about (light-emitting) diodes?
  We need resistor, LED, and power source. 
  LED is a device that emits light. LED by itself has anode(+) and cathode(-). The first one usually longer than the latter.
  1. It has only one way connection from + to -
  2. Doesn't produce heat because there is a process called electroluminescence.


- Why esp8266?
  Because they are very good in terms of price and quality
- What is personally inspiring for you?
  That I actualy can build something valuable for that low price
- What is the connection to coffee?
  It costs as cheap as a cup of coffee, but it's more valuable



- lookup 1 other MCU online
  The Arduino Uno is a widely-used microcontroller board based on the ATmega328P microcontroller. It features 14 digital input/output pins, 6 analog inputs, and operates at a 5V logic level.
- note 2 (dis)advantages of the Wemos D1 Mini vs other MCUs, note down 1 way this might impact your work
  Advantages:
  1. Unlike many traditional MCUs, the WeMos D1 Mini comes with built-in Wi-Fi capabilities
  2. Its small size makes it ideal for projects with space constraints
  Disadvantages:
  1. The WeMos D1 Mini offers only one analog input pin
  2. Operating at 3.3V logic levels, it may pose compatibility challenges

  If your project involves multiple analog sensors, the single analog input of the WeMos D1 Mini could be a limitation

- Mini Project: LED-button
[Calculations](../Module1/Pictures/02-calculations.jpg)
[What we built](../Module1/Pictures/02-mini_project.jpg)

- [Connecting LEDs in parallel](../Module1/Pictures/02-parallel_connection.jpg) 
- [Connecting LEDs in series](../Module1/Pictures/02-series_connection.jpg)


- Mini Project: Relay-Lock-Button
[Relay before](../Module1/Pictures/02-relay_project.jpg)
[Relay after](../Module1/Pictures/02-last_project.jpg)

- Normally open normally closed?
  It depends on where you connect cable. 
  1. If you plug cable into right socket then it's normally closed
  2. If you plug cable into left socket then it's normally open