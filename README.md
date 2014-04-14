Oculus FPV
===========

English info
------------
Code for TPG4850 eksperter i team vr-landsbyen. Video of it running is available [here](https://www.youtube.com/watch?v=33uHzDvxB00).
This is a project where we use an Oculus Rift to display stereo video from a quadcopter, and rotate the cameras on the quadcopter based on head rotation.


Info
----
I mikro mappen ligger koden som er skrevet for mikrokontrolleren p� kretskortet. Tar seg av � styre servoene basert p� input den f�r fra en mottaker.

I pc mappen ligger koden for programmet som kj�rer p� pcen. Leser inn en videostr�m fra to usb enheter og viser dem p� oculus rift, og leser hodebevegelser fra oculus rift og sender opp til flyet. I mappen ligger ogs� graf-filene som setter opp direct show grafen, oculus bibliotekene som er brukt samt bibliotekene for breakout-kortet.

Bygging
-------
For � bygge programmet som kj�rer p� PCen kreves det at man har Windows SDK installert. Prosjektet b�r v�re konfigurert slik som OculusWorldDemoapp som f�lger med n�r man laster ned Oculus SDK. Alts� at CommonSrc er inkludert og at libraries er lenket til i kompileren. S� m� man legge til include filer og libraries for directshow, og for breakout-kortet.

Kildene til dette finnes i rapporten.


license
-------
The code is released with the Apache 2 license where possible, and the needed license where the code is a derivative work.
