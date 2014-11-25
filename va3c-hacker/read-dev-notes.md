Dev Notes
===

2014-11-23 ~ Theo

* Add open JSON 4 files using file dialog
* Add monitor file modifications 

The monitor part took longer than expected, but produced the file open by file dialog function as well as a nice start to 
hack the request animation frame functionality. And the monitoring seems to work a treat.

Looked at [ThreeFab]( http://blackjk3.github.io/threefab/ ) and [ThreeNode]( http://idflood.github.io/ThreeNodes.js/public/index.html ).
Both nice and would be great geometry editors but both appear to be currently broken.

http://va3c.github.io/viewer/va3c-hacker/r2dev/va3c-hacker-r2dev.html#enable-file-modified-monitor.js

2014-11-22 ~ Theo

It would be great to be able to add geometry. But do we really want to build a full geometry editor?
Especially when there are some great editors out there already?
Why not just read their JSON output in near-real-time?

Stand on the shoulders of giants: or at least: use their apps.
 
* Add R2 dev
* Add JSON drag and drop capability
* Working on draggable objects with limited success

2014-11-21 ~ Theo

* Preparing to publish R1
	* Arching files
* rename some items from 'view' to 'browse' - where 'browse indicates you can use the file, whereas 'view' is more read only
* Add read Readme
* Code clean-up
* Add Three.js Inspector
* Add JSON 4 loader


2014-11-20 ~ Theo

* Continue building AA Adventure
* Looking into adding Three.js Inspector

2014-11-18 ~ Theo

* Fiddling with location hash and parameters
* Cleaning up callback issues. using more location.hash
* Building AA demo
* Added more templates

2014-11-16 ~ Theo

* code clean-up. renaming files. put files in archive
* battling with location.hash and callbacks but three load files turned into one file


## 2014-11-15 ~ Theo
21:59 ~ Code clean-up
22:30 ~ Menus beginning to toggle nicely
00:03 ~  Still working on animation callbacks 

## 2014-11-12 ~ Theo
11:39 ~  Started these notes and adding to menu
11:56 ~  read-dev-notes.js now working.
Coding going well - but only after a usual bout of callback insanities. What would the fun of coding be if it did not drive you around the bend from time to time?

Some of the notions behind this project are:

vA3C viewer is becoming more and more complicated. Even I can't understand it. Something very simple is needed. Very 'Hello, world!'-like. 
So lots of tiny, cookbook examples that you can assemble as if they were Lego blocks. Every function in its own file.
Every file name highly descriptive of the function inside.

My old friend Henrik Bennetsen taught me a nice lesson when he said: You don't have to go to 'it]. 'It' should come to you." 
So, for example, instead of just providing a link to the Glam files, the Hacker brings them into your screen. Now you have something you can play with. 

The code to build a user interface can become complicated very easily.
User interface content co-mingled with code becomes in-editable after a while.
People who use GitHub know Markdown. People who post on Reddit use Markdown. 
So write the content for the user interface using Markdown. And put the code somewhere else.
An interesting mechanism for connecting user interface content with user interface code is via the use of location.hash.
 
13:58 ~  Added more nasa objects. Load-file-stl now removes previously loaded stl files when asked to do so with 'open#' in the hash.



15:09 ~  Fixed up more of Tony's <glam> demo and example files. 

17:44 ~  Bringing in JSON 3 files. Added 'View files from 3D Warehouse' - which has a scale feature. Alse we are speaking with an English accent

## 2014-11-10 ~ Theo

Project was started. Could not face another session of parsing the complexity of the vA3C viewer.