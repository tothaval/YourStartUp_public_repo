# YourStartUp_public_repo
start up helper tool for smooth starts into projects, be them everyday projects or business related, catching of thoughts via scetchboard, notesfunction etc.

project got a bit out of hand, if you'd like, you may assist or develope further.

license concept idea:
1.
free with payoption to me and all participants of the development group, equally shared
2.
acknowledgement of authorship and extended authorship
3.
if advertising is part of a fork or an application conzept, they have to follow the following design principles: - closable, resizeable, (audio protection, video control), and moveable
4.
free in terms of distribution and free to use
5.
no garantie for further development, no support possible as of yet
6.
if you represent a company or a business, you can pay any sum and receive a bill with german tax percentage(or if a sort of a foundation is founded, the tax percentage from that foundations location) to use the software with a costfactor or the right to distrute descendant concepts of the software with a costfactor
7.
first concept code snippets/files, which are functional, are considered original code(oc), oc has to remain unaltered, copies can be altered and redistributed freely.

dev (/team())
dev0: stephan kammel
version 0-24
time of creation(TOC): may - september 2022
intention:
offering an easy to use software, to handle file management, to assist others in their projects, to draw, to capture ideas and the daily necessities of life.

use concept:
a.
dragable graphical containers, right click closing of any dragable graphical ui container, dragging with leftclick or middleclick
b.
recoloring with leftclick or middleclick
c.
since i am an beginner level programmer and c# and wpf are new to me, i may have missed better ways of solving the problems, but it works
and worked quite well, that is why i will put up 3-4 different versions for now, which cast a light on to possible development directions,
i have many more(as mentioned above) if necessary, at least on my machine, which is currently an ryzen5 apu, some versions run really smooth.
d.
there is an info button which contains a sort of a manual, goal is, that all programms, files or images can be opened with a single click, the binding to the
clickable surface should be resetable easy, the clickable surface should be deleteable and every surface should be resizeable and renameable.
e.
all surface elements of YRS shoud be redesigneable by the user, meaning every color, every textitem etc. should be subject to the will of the user in regards to appearance and visual feeling

handling:
1.
download the zip files, unpack them, enter the folder structure, until you find /bin/debug or /bin/release, 
 within, there is an .exe named yourstartup.exe, double click to run
2.
currently this application concept runs only on windows, tested under win 11, win 10 and win 8, since i developed this for my brother, who has a win 11 and a win8 machine, it has/had to run on win8, that is why i choose net.core 4.60., which is not relevant to keep, if the intent can be fulfilled with later versions of net core
3.
fast edit user configuration in /bin/debug/files/ or /bin/release/files, i named them save.[FUNCTION], but they are simpel textfiles, easily editable.
4.
where there is a scetchboard function with F2 savemode, there will be a folder /bin/debug/files/pictures or /bin/release/files/pictures
5.
if you want do develop or bugfix, open the solution file(check if debug mode is debug), f.e. in project version YourStartUp_v_1_11_NET_4_6 it would be YourStartUp_v_1_11_NET_4_6/yourstartup.sln
6.
developed in wpf and c#, using free version of ms visual studio 2019 ((thx to ms for a free ide.)

overview:
- some scetchboards and some YRS main windows allow file drop, or image file drop
- the general ram usage is very low atm, 
- you can put many many pictures within one scetchboard
- you can already layer some objects via z-index, you can rotate them, you can delete them with a single right click, as well as the hole application
- some objects can already be initialized with an dimensional size, others not, because of some bugs.
- i did not do any bugtracking, just fixed most of those standing in the way of a functional or in a way functional prototype.
