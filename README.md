# fotoslider

This is the "foto slider" script for our motor driven camera slider. 

Module        : main module, foto.py
Author        : Swen Hopfe (dj)
Design        : 2019-12-17
Last modified : 2020-01-10

The python script works on Raspberry Pi 2/3/4/B/+ with TFT display and keyboard and was tested on a Pi 3B. There is a X-interface based on tkinter available. Beside you can use terminal mode or a remote ssh connection. Libgphoto2 is integrated, Nikon or Canon cameras works fine with it.    

Keyboard shortcuts:

r   -  Reboot
s   -  Shutdown
x   -  Programm beenden
t/i -  Stepper-Test / Input-Test
n   -  Nullung
1/a -  Fahrt nach links / ohne Endstop!
2/b -  Fahrt nach rechts / ohne Nullung
3   -  Linksschwenk 180 Grad
4   -  Rechtsschwenk 180 Grad
5   -  Programm 5 (2M-Slide r-l)
6   -  Programm 6 (2M-Slide l-r)
7   -  Programm 7 (3 Aufnahmen linear)
8   -  Programm 8 (90 Grad in 5 Aufnahmen)
9   -  Programm 9 (360 Grad in 20 Aufnahmen)
h   -  Hilfe (diese Ausgabe)
c   -  Kamera ausloesen

Just read the script, feel free to modify and have fun!
