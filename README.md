# YourStartup UserInterface(YS UI) public repository

dev (/team())
dev0: stephan kammel

version 0.9.7.1
time of creation(TOC): may - october 2022

intention:
offering an easy to use software, to handle file management, to assist others in their projects, to draw, to capture ideas and the daily necessities of life.

YS UI is a versatile software designed to help users in their projects or hobbies.
It started as a tool to open files and programs fast with a single click via a button.
Since then it has grown quite a bit.
At the current stage it is quite easy to use via mouse and a few key bindings. Every
element on the canvas follows the same principles, they can be moved, their appearance
on the canvas can be altered, they can be deleted and they can be generated with a click
on a button or via hotkey.
Files and URLs can be bound to elements and afterwards opened with a single click. It
is easy to arrange all the required elements on the screen. Thanks to the possibility 
of a fully or mostly transparent window, it can also be used as an overlay to block unwanted
clicks or if semi transparent, you can use it as a filter to change the color of other
software. the dimming of light intensities can be quite relaxing for the eyes.
The user can change the design of YS UI. 
YS UI has various drawing features and it is very easy to generate quite diverse pictures
with just a few clicks.
YS features various elements with different functions and features. They all have in
common that they aim to provide assistance for day to day trivialities, duties or hobby
or project related activities.



in terms of license: if an existing license model covers and features the following points
or is very close to their intentions, it is likely that such a license model will be chosen

license concept idea:
1.
free, but with a payoption for users or enterprises who want to pay if they like the software
and are happy with it
2.
acknowledgement of authorship and extended authorship
3.
if advertising is part of a fork, an application concept or of a plugin element as an addition to ys ui,
the following design principles must apply: - the element with the ad must be closable, resizeable and
moveable, the user has to be able to control the intensity of the influencing methods, be they sounds, light
or other.
4.
free in terms of distribution and free to use
5.
no warranty for further development at the moment, no support possible at the moment (this may change if more people join the project)
6. ?
7. ?


use concept:
a.
dragable graphical containers, right click closing of any dragable graphical ui container, dragging with middleclick
b.
recoloring with leftclick
c.
goal is, that all programms, files or image files can be opened with a single click, the binding to the clickable surface
should be resetable easy, the clickable surface should be deleteable
e.
all surface elements of YS UI shoud be redesigneable by the user, meaning every color, every textitem etc. should be subject
to the will of the user in regards to appearance and visual feeling


handling:
1.
download the latest version zip file, unpack them, enter the folder structure, until you find /bin/debug or /bin/release, 
 within, there is an .exe named YSUI.exe, double click to run
2.
currently this application concept runs only on windows, tested under win 11, win 10 and win 8, since i developed this for
my brother, who has a win 11 and a win8 machine, it has/had to run on win8, that is why i choose net.core 4.61., which is
not relevant to keep for all variants or versions of this software
3.
canvas pictures can be taken with F2 savemode, there will be a folder /bin/debug/files/pictures or /bin/release/files/pictures,
there you can access the pictures
4.
if you want do develop or bugfix, open the solution file(check if debug mode is debug), f.e. in project version
YourStartUp_v_1_14_NET_4_6 it would be YourStartUp_v_1_14_NET_4_6/yourstartup.sln, in YSUI it would be YSUI/YSUI.sln
5.
developed in wpf and c#, using free version of ms visual studio 2019 ((thx to ms for a free ide.)


overview:
- YS UI and some of its elements allow file drop and/or image file drop
- the general ram usage is very low atm
- you can put many many pictures within one instance of YS UI
- you can layer objects via z-index, you can rotate them, you can delete them with a single right click
- some objects can be initialized with custom dimensional size values
- shapes can be saved and loaded with positions and rotation, but not yet with colors, still working on that
- most elements can be saved with positions, but not yet with rotation, colors or contents, still working on that


- the project is in alpha stage, up until now, intensive testing was not possible, i identified and
fixed most of the bugs standing in the way of a functional or in a way functional prototype
- the project was only tested on 3-4 different machines
- if you have a laptop, use an external mouse, otherwise it will not be possible, to use ys ui to its full extend,
since it needs the middle mouse button and i did not yet develop an alternative handling method for hardware with
no mouse
