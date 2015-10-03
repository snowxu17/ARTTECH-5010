---
layout:     assignment
categories: assignment
title:      Assignment 3
subtitle:   Serial Communication
author:     bakercp
date:       2015-09-25 00:06:00
due:        2015-10-02
---

1. Make sure everything is complete from _Assignment 2_.
    - Please take time to review the Cylon Example.
    - Key questions you are expected to be able to answer after this week.
        - What is analog to digital conversion? (ADC)
            - How and when do you use it on an Arduino?
        - What is digital to analog conversion? (DAC)
            - How and when do you use it on an Arduino?
        - What is sampling frequency and why is it important to have a "fast" sampling frequency?
        - What are the SI units of frequency?
        - What is the difference between sampling frequency (`fs`) and sample resolution (aka bit depth)?
        - What is the formula for figuring out the number of "levels" that can be represented given a finite number of bits?
        - What is the sample resolution of a typical Arduino's 10 bit ADC?
        - What is the `AREF` pin for on an Arduino?
        - What is a "voltage divider" and how is it often used with the Arduino's analog input?
        - Draw a typical voltage divider circuit for hooking up an analog input (such as a photo cell) to an Arduino.
        - How does the Arduino simulate digital to analog output?
        - What is PWM and what is it used for?
        - What is a duty cycle?
        - How do PWM "frequency" and PWM "duty-cycle" differ?
        - What are pull-up and pull-down resistors and why are they needed?
        - Draw a typical pull-up and pull-down resistor circuit.
        - What is a typical values for a pull-down resistor when working with the digital input?
        - What is an array?  
        - Why might you use an array?
        - How do you access the elements inside an array?
        - How do you access the elements in an array using a `for-loop`?
        - Why might programmers call the first element in an array the zero-th rather than the "first"?
    - If you are unsure of the answers any of those questions, look it up or check your notes.  If you are still are unclear post a question to the forum and we'll discuss it.

2. Serial Communication Reading
    - [Schematics](https://learn.sparkfun.com/tutorials/how-to-read-a-schematic)
    - [Serial Communication](https://learn.sparkfun.com/tutorials/serial-communication)
        - Make sure you understand what an [Ascii Table](http://www.asciitable.com/) is.
    - [Hexadecimal](https://learn.sparkfun.com/tutorials/hexadecimal)

3. Required tutorials (for these, you may use Processing or Max/MSP or openFrameworks if you like).
    - [Debounce](https://www.arduino.cc/en/Tutorial/Debounce)
    - [ASCIITable](https://www.arduino.cc/en/Tutorial/ASCIITable)
    - [SerialCallResponse](https://www.arduino.cc/en/Tutorial/SerialCallResponse)
        - Note, you don't need force resistors for this example.  Simple buttons will suffice.
    - [SerialCallResponseASCII](https://www.arduino.cc/en/Tutorial/SerialCallResponseASCII)
        - Note, you don't need force resistors for this example.  Simple buttons will suffice.
    - [SerialEvent](https://www.arduino.cc/en/Tutorial/SerialEvent)