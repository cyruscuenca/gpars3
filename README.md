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
##### DO NOT USE PLA!
I kept using PLA with my pens, and broke a whole bunch. I wasted a lot of money, so take my word and
use ABS.


__Here are a few videos I have on my YouTube channel:__

https://www.youtube.com/watch?v=36_p1c6M734

https://www.youtube.com/watch?v=ibm2scWGx3Q

In the future, I'll post a coule tuturials to make it easier to make a LEGO 3D printer.

---
## Configuration

All of the config variables are located between line 45 and 70.

I have a sytem of finding variables(for people not familiar with text based code) that utilizes
comments.

__To find something referanced in my video tuturials:__
1. Press CTRL + F 
2. Type ":"

__Then, with no spaces, and in lowercase,__
3. Type the keyword I say
4. Click enter

| |   Reference words |
|---|--------------|
|:  |startposition |
|:  |degreestomm   |
|:  |startseq      |
|:  |endseq        |
|:  |power         |


## Credits

 __Cyrus Cuenca:__ http://cyruscuenca.blogspot.com
I build the the hardware, work on the parser, make the videos, and the document the LEGO printer.

__Xander Soldaat:__ http://botbench.com
Is a HUGE help with the programming :grinning:

__Marc-Andre-Bazergui:__ http://bazmarc.ca
Built the first LEGO 3D printer using a 3D pen. His used a math program to make shapes.

__Thomas Madeya:__ nano-giants.net
Made the math program for Marc.

---
## License

Creative Commons Attribution-NonCommercial 4.0 International Public License

Read LICENSE.md for more info(It's really long :unamused:).

## Contact

Email Cyrus at: cyrushcuenca@gmail.com for questions.
