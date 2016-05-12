# G-PARS3

![image one](https://github.com/cyruscuenca/g-pars3/blob/master/media/3Dprinter_header.jpg)


## Description

This is a g-code parser written in ROBOTC for a LEGO 3D printer I'm making. 

https://www.youtube.com/watch?v=ibm2scWGx3Q

## Configuration

All of the config variables are located between line 45 and 70.

```
This is where you specify your starting position(default 0).
float xAxisPosition = 0;
float yAxisPosition = 0;
float zAxisPosition = 0;

//This is where you specify the degrees to mm so the program can compensate properlydefault 8).

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
