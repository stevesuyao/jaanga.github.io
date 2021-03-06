﻿<span style=display:none; >[You are now in a GitHub source code view - click this link to view this read me file as a web page]( http://jaanga.github.io/gestification-r2/jest-hands-leap-threejs/ "View file as a web page." ) </span>
<input onclick=window.location.href='https://github.com/jaanga/jaanga.github.io/tree/master/gestification-r2/jest-hands-leap-threejs/'; type=button  value='You are now in a GitHub web page view - Click this button to view this read me file as source code' />

[Jaanga]( http://jaanga.github.io ) » [Gestification R2]( http://jaanga.github.io/gestification-r2/  ) »

[Jest Hands Leap Three.js Read Me]( index.html )
===

<!--
[Draw the Line Leap Three.js - Demo - Dev Revision - Full Screen]( http://jaanga.github.io/gestification-r2/draw-the-line-leap-threejs/dev/ )

## Web Page / Source Code

<iframe class=ifr src=http://jaanga.github.io/cookbook-html/templates/code-edit-view/code-edit-view-r2.html#http://jaanga.github.io/gestification-r2/draw-the-line-leap-threejs/r1/draw-the-line-leap-threejs-r1.html width=100% height=600px ></iframe>  
###### _Draw the Line Leap Three.js - Dev revision - Code Edit View_ / [Edit full screen]( http://jaanga.github.io/cookbook-html/templates/code-edit-view/code-edit-view-r2.html#http://jaanga.github.io/gestification-r2/draw-the-line-leap-threejs/r1/draw-the-line-leap-threejs-r1.html  )
-->

## Concept

### Issues / Problems
<!--

The general format is an adaptation of the ideas developed in Alexander's _et al_ [A Patttern Language]( https://books.google.com/books?id=hwAHmktpk5IC&pg=PR10#v=onepage&q&f=false ) - as sammarized on page 10.

Each pattern describes a problem which occurs over and over again in our environment, and then describes the core of the solution to that problem, in such a way that you can use this solution a million times over, without ever doing it the same way twice.

patterns are descriptions of common problems and proposal for the solutions that can be used repeatedly every time the problem is encountered and producing an different outcome.

-->


### Mission
<!-- a statement of a rationale, applicable now as well as in the future -->

* To create, record and replay character animations of hands 

### Vision
<!--  a descriptive picture of a desired future state -->

## The Scripts

### jestLive Skins BVH

[jestLive Skins BVH - Dev - Demo]( http://jaanga.github.io/gestification-r2/jest-hands-leap-threejs/jest-live-skins-bvh/dev/ )

[jestLive Skins BVH - Source Code]( https://github.com/jaanga/jaanga.github.io/tree/master/gestification-r2/jest-hands-leap-threejs/jest-live-skins-bvh )

* Capture Leap motion data in real time and use to create hand visualizations in real-time
* Translates Leap data into BVH 'bones' which are then used to update Three.js geometry in the role or position of 'bones'
which are then linked to a 3D mesh or 'skin' that reprsents a hand


### jestLive Bones BVH

[jestLive Bones BVH - Dev - Demo]( http://jaanga.github.io/gestification-r2/jest-hands-leap-threejs/jest-live-bones-bvh/dev/ )

[jestLive Bones BVH - Source Code]( https://github.com/jaanga/jaanga.github.io/tree/master/gestification-r2/jest-hands-leap-threejs/jest-live-bones-bvh )

* Capture Leap motion data in real time and use to create hand visualizations in real-time
* Translates Leap data into BVH 'bones' which are then used to update Three.js geometry in the role or position of 'bones'


### jestRecord BVH

[jestRecord BVH - Dev - Demo]( http://jaanga.github.io/gestification-r2/jest-hands-leap-threejs/jest-record-bvh/dev/ )

[jestRecord BVH - Source Code]( https://github.com/jaanga/jaanga.github.io/tree/master/gestification-r2/jest-hands-leap-threejs/jest-record-bvh )

* Capture Leap motion data in real time and use to create hand visualizations in real-time
* Translates Leap data into 'bones' which are then translated to BVH data and can be saved to a file in BVH format


### jestReplay BVH

[jestReplay BVH - Dev - Demo]( http://jaanga.github.io/gestification-r2/jest-hands-leap-threejs/jest-replay-bvh/dev/ )

[jestReplay BVH - Source Code]( https://github.com/jaanga/jaanga.github.io/tree/master/gestification-r2/jest-hands-leap-threejs/jest-replay-bvh )

* Read a BVH format data file, create a set of 3D 'bones', replay the data through the bones


## Things to Do / Road Map

_To be added: the record and replay Leap JSON files scripts_

The majority of this effort was completed in 2013 and - sadly ~ much was left unfinished.
The good news is that most everything still works even though much in Three.js and in JavaScript has changed.

Things that need work include:

* Improving the accuracy of the positions of the fingers
* Adding more bones demos
* Adding more skinned hands demos
* Cleaning up the code and bringing all the files up to the latest state-of-the-art


## Features


## Issues

 
## Sources


## Contact

* jaanga@googlegroups.com

## Copyright and License

* [Copyright and License]( http://jaanga.github.io/#http://jaanga.github.io/jaanga-copyright-and-mit-license.md ) 

***

<center title="dingbat" >
# <a href=javascript:window.scrollTo(0,0); style=text-decoration:none; >❦</a>
</center>

