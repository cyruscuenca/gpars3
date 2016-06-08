# G-PARS3

![image one](https://github.com/cyruscuenca/g-pars3/blob/master/media/3Dprinter_header_2.jpg)


## Description

This is a g-code parser written in ROBOTC for a LEGO 3D printer I'm making. My printer uses LEGO linear actuators driven by LEGO motors with build in encodors which allows me to track the position of the print head.

The extuder is a 3D printing pen I bought off Amazon.com http://www.amazon.com/Soyan-Drawing-Printing-Printer-Filament/dp/B00PTW7WEQ

These pens are sold my a variaty of sellers, and they sometimes get misslabeled. Sometimes they'll say the pen can use PLA and ABS(types of plastic). DO NOT USE PLA!

I kept using PLA with my pens, and broke a whole bunch. I wasted a lot of money, so take my word and use ABS.

Here are a few videos I have on my YouTube channel:
https://www.youtube.com/watch?v=36_p1c6M734
https://www.youtube.com/watch?v=ibm2scWGx3Q

In the future, I'll post a coule tuturials to make it easier to make a LEGO 3D printer.


## Configuration

All of the config variables are located between line 45 and 70.

I have a sytem of finding variables(for people not familiar with text based code) that utilizes comments.

To find something referanced in my video tuturials:
1. Press CTRL + F 
2. Type ":"

Then, with no spaces, and in lowercase,
3. Type the keyword I say
4. Click enter

The words I'll reference are:

|-----------|
|-----------|

```
This is where you specify your starting position(default 0).
float xAxisPosition = 0;
float yAxisPosition = 0;
float zAxisPosition = 0;

//This is where you specify the degrees to mm so the program can compensate properly(default 8).

long XdegreesToMM = 8;
long YdegreesToMM = 8;
long ZdegreesToMM = 8;
```

Specify your degrees to mm if you're not using the linear actuator modules I am in the second block of variables. 

Specify your starting position if you don't want to start at 0, 0, and 0.

## Credits

Cyrus Cuenca(me): http://cyruscuenca.blogspot.com

Xander Soldaat: http://botbench.com

Marc-Andre-Bazergui: http://bazmarc.ca

## License

Creative Commons Attribution-NonCommercial 4.0 International Public License
[read the LICENSE.md]
