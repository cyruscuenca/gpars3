# G-PARS3

![image one](https://github.com/cyruscuenca/g-pars3/blob/master/media/3Dprinter_header_2.jpg)


## Description

This is a g-code parser written in ROBOTC for a LEGO 3D printer I'm making. My printer uses LEGO linear 
actuators driven by LEGO motors with build in encodors which allows me to track the position of the 
print head.


This is extuder is a 3D printing pen I bought off Amazon.com:

http://www.amazon.com/Soyan-Drawing-Printing-Printer-Filament/dp/B00PTW7WEQ

These pens are sold my a variaty of sellers, and they sometimes get misslabeled. Sometimes they'll say 
the pen can use PLA and ABS(types of plastic). 


__DO NOT USE PLA!__ I kept using PLA with my pens, and 
broke a whole bunch. I wasted a lot of money buying pens, so take my word and use ABS.



Here are a few videos I have on my YouTube channel:

https://www.youtube.com/watch?v=36_p1c6M734

https://www.youtube.com/watch?v=ibm2scWGx3Q

In the future, I'll post a couple tuturials to make it easier to make a LEGO 3D printer.

## Inistial Calibration

All of the config variables are located between line 45 and 70.

I have a sytem of finding variables(for people not familiar with text based code) that utilizes
comments.

1. Press CTRL + F 
2. Type "__:__"

Then, with no spaces, and in lowercase,

3. Type one of the keywords below
4. Click enter

| |   Reference words |
|---|--------------|
|__:__  |startposition |
|__:__  |degreestomm   |
|__:__  |startseq      |
|__:__  |endseq        |
|__:__  |power         |

:startposition should be 0, 0, 0, unless you are starting at an offset position.

:degreestomm should be how many degrees a mottor needs to turn in order to move one mm. You can use the port view tool to find the proper value for eah motor.

:startseg here, change how many degrees your extruder motor needs to move in order to press the extruder button.

:endseq, same, except enter the value X -1.

:power set your motor power. You must fine tune this your self. Because there's a bit of a pause between motor movements, if you go too fast, thicker globs will be deposited on corners. You can get rid of these by lowering your speed.


## Credits

 __Cyrus Cuenca:__ http://cyruscuenca.blogspot.com


__Xander Soldaat:__ http://botbench.com

This was my first C project, and Xander walked me through it.


## License

Creative Commons Attribution-Non Commercial 4.0 International Public License

Read LICENSE.md

## Contact

Email Cyrus at: hello@cyruscuenca.com for questions.
