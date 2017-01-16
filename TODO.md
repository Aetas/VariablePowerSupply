* Y-cap?  
Seems to only be needed for switching/flyback at high voltages.  
The primary side of the transformer does not share common/gnd with the secondary side. The board is entirely 32VDC or less at no more than 3 surge amps, ~2 in operation

* negative voltage regulator on LTSpice.  
Could ghetto invert it on both sides to create an element that does the same thing.  
LTSpice claims to have a neg Voltage regulator, but I don't have it. Somehow.

Might want to choke the AC input. Probably should choke the AC input.  
Could just wrap a ferrite bead like Oople. (http://www.righto.com/2012/05/apple-iphone-charger-teardown-quality.html)  

Make sure the size of the relief holes are big enough. They look rather small but it might just be the pads large size.

Triple check trace width. They're over sized right now but I assumed the density and fill.

Scrap the whole project for the most beautiful programmable switching flyback power supply the world has ever seen. (Good joke, right?)  
I might actually want to do this in the future when I want a less noisy fixed 5V supply. Really I should just revisit my old supply and measure the noise.
