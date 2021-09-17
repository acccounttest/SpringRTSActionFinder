ACTIONFINDER
 # Post by Senethril » 13 May 2021, 18:29

cmd_actionfinder.lua
(37.92 KiB) Downloaded 17 times
---
Hello i am a player that usually turn around official SL and unofficial mando and ares hosts, i do not much beyond all reasons and others communities.

I want share with you a widget, Senna, a player that i appreciate, highly probably hacked me, he say its me directly but he is the most powerfull admin and compute all his games, he is probably the only one that constantly ban, but that not stop the new arrivals, he try feign he is not aware of AI and widgets .., but who is this each time ?, a cool teammate ...

One txt and lua file in one rar of 10,1ko.
txt abstract:

TUTORIAL
--------

This script help user to not miss any action against ally units, the aim is provide a way to go to last war(or/and eco) actions directly(smoothly),to protect to not be too invasive as the script change the view automatically, a counter of 3 or 1 seconds is necessary renewed with mouse and keys activation, can be broken so need to be reloaded, can be faster in the way you ll discover, usually consecutive camera position in a second.

Script was intended to be used for a spec, for a presentation show in a market or in public, in LANS etc.
It seems though ages and mods, the choice between eco mode and warmode cannot be well differentiated and eco mode is needed for script computation and continuation or exceptionally temporally allowed but need to be reset to default by pressing the appropriate key T.
This is broken and needs to be reloaded(not entirely hopefully), script can be blocked into track mode in a unit, like u press T key, but this key was remodified, it does not lock on a unit but shows a special view transition of the horizon for fun.
It's more complicated, originally the script worked in FFA mode(but not as player except if you wanna know every enemy unit attacked and not only yours and teammates ?), so as spec it worked in all teams possible, but since updates, the team is locked and chosen by the last unit selected or at start, so you only catch event lists of one team at time.
This can be avoid with trick and widget order list and by deactivation of adv list information and another widget i dont remind, it make and show the last team selected, if you can't find a clue, try this, load game as spec with already units everywhere, select all units, deactivate most widgets possible, when all is selected spam the key T, normally you should non stop switch unit selectionned and teams too, after 5 seconds, try press R key and click(or not), change team, reload, ALT+E ... try something it can works too as exceptional change but finally one time or two is not enough , right ?.

The second behaviour is continue the auto redirect but only very near the screen coordinates positions, this is achieved more easily but less and less with the key O, the key O first aim was track a unit in FPS mode(not move in FPS but more see what unit see, except when u leave it just upper, old aim was turning around completely 360°) and switch from a unit to another without break the camera transition with possibility to change the speed between the two in real time with the mousewheel, but the mouse wheel change in real time is not limited so it can be stuck in very slow mode, default without the two script is 0 and granular move, the more you smooth the more you are slow and more command are slow, but with higher speed you can easily recuperate and compensate the lack of precision and anticipation, you need find how to unlock this with keys and the script, add a range if you want and try change some camera view parameters.
I think the best is rewrite this script to be used without smoothscroll or hybrid overhead camera widget, this last permit new and old view modes, and add unique functionality, possibility to see and look around not you but the mouse pointer, so you can flip the map at start and choose to see the enemy to the horizon instead need concentrate on others map positions, this require compute the shape of the map and use numpad to lock the screen on the zone at start, good luck.

Rule0
-----
Without the widget named smoothcam(normally included by the mod or under another widget name, else modify default smooth here everywhere necessary) activated only after this widget(not necessary in the list of widget with F11 but has to be manually if other was manually reloaded, or at start if your widget list configuration is not rewritten for the load order and not the order seen as list), can produce an abnormal speed of move of the camera, else its very slow, it should be changed in real time using smooth scroll but maybe you are too tard to do that while playing or devs are no more in vacation and script is broken.

Rule1
-----
As a player(unlike spec) it's better to activate the script by pressing 2 times the combinaison, ALT+E, then messages appear in the console, showing nothing important.
Needed to be re-executed in case nothing happened, there are two modes, eco mode only and battle mode only events.
if you deactivate the eco mode(T) , you ll have to repeatedly repress this rule, ALT+E more often, so use regularly the only fight mode is not usable, but anyway it's very rare to be stuck in a eco area, rather track on a unit, then spam MMB and mouse buttons should be enough.

Rule2
-----
Pressing y switch between 1 second and 3 seconds for renewal of the view auto redirects.

Rule3
-----
Middle mouse button clicked renew the second counter(let it press idk cause i use only the original cursor, so when MMB then you can drag mouse locked with the view of the screen and you navigate the map easily and faster without need modifier keys, without need to go to borders and edges), if not enough press it two times then auto is locked.

Rule4
-----
Press left click reactivate the search for redirections.

Rule5
-----
Moving mouse continuously, stop temporarily the redirections.

Rule6
-----
Press R key(spam thats a fuc*** key), change directly the view as soon as possible, and at least activate the search and auto redirection(these two diff are unclear).

Rule 7
------
Save two camera positions(save stop redirections of the view, load position reactive it or R)

X=save1
C=save2

V = load X
B = load C

Another in case of:
S=save3
N = load S

Script activation=save0
ALT+E=load0
Quit script or minus key - (not NUMPAD) =load0

The - key can be broken, on my computer it lowers the sound volume as well in both keys of
the keyboard(show only error and quit script if no pos were saved previously).

KEYS USED IN THIS SCRIPT
------------------------
X S Y M C O
-
R E T F G N V B

INTALL IS
USER/MY DOCUMENTS/MY GAMES/SPRING/ENGINE/10X.X/LuaUI/Widgets/ even for TA test versions
OR
USER/MY DOCUMENTS/MY GAMES/SPRING/ENGINE/10X.X/LuaUI/Widgets_BA for any test versions if nec

https://mega.nz/file/qxxghJja#XZ8cofGyN ... IMtAY41ans
---
Top
User avatarBeherith
Moderator
Posts: 5076
Joined: 26 Oct 2007, 16:21
Re: ACTIONFINDER
 # Post by Beherith » 15 May 2021, 15:02
---
Im sorry, but I have no idea what this widget actually does/prevents/detects :( Could you post some image examples please?
---
Top
Senethril
Posts: 42
Joined: 04 Oct 2013, 18:20
Re: ACTIONFINDER
 # Post by Senethril » 16 May 2021, 02:42
---
No i cant, if i do i ll need tons of images, theses are randomly and independently of the script, the script is essentially made for noobs, sorry its not a tutorial, this script is not the spell what's best direction i need like in skyrim, you have three problems to solve in this:

How can i choose event in a queue and conduct though all in a row.

Achieve this piece of shit by disabling and editing keys to your need and compatibles layouts.

Kill it and add it into next BA version.

Thx you for the interest but i think you should say me the truth and stop say you know nothing, maybe you have no idea how the script can't achieve it's purposes and finalities, me too, or maybe this is really a piece of ****.

:D

Long live to sandofmines map, happy is queen of the sands. :|
---
Top
User avatarPtaQ
Posts: 180
Joined: 15 Sep 2009, 10:40
Re: ACTIONFINDER
 # Post by PtaQ » 16 May 2021, 10:54
---
I must say PicassoCT posts look quite comprehensible after I read that.
---
