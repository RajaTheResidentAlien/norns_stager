# norns_stager
(development starting points)

instructions:

* install as instructed below in the 'download' section
* if you want to try out the 'dregz.lua' accompanying max patch(for synchronized visuals), download that patch to your computer(you can visit the github link in the 'install' line below, and just download the .zip, then throwaway everything else but the max patch found in the 'lib' folder: "AlienFBMEye.maxpat"), open it in Max, and activate the toggle near the left-hand side of the patch:
![Screen Shot 2021-12-29 at 10.51.02 PM|690x343](upload://icRIg8g6zasUFCdzjaYKKNvXYvQ.png)

* since these are more like single songs, i'd recommend easiest thing is to control from within maiden: select either script to try it out('simpy.lua' or 'dregz.lua') and hit the play button in maiden, then it's easy to just hit the stop button, otherwise, if you select the script from within your norns, to stop the script you'll just need to 'clear' it(hold k2 then k1 in that order, then confirm when it asks 'clear?' with k3)

* 'simpy.lua'- simple random melody playing from a table of notes(example for myself of the simplest thing i could create; a reminder of the basics of engine creation)

* with 'dregz.lua', if you hold down the k2 key, it'll push the audio through the resonator effect(dynklank with resonant frequencies in the key of the piece), if you hold down the k3 key, it'll push the audio through the tap-delay, if you hold down both, it'll go through resonator and then through the tap-delay...
the knobs control 'bpm', 'beat-division', and 'swing', in that order for enc1, enc2, & enc3

more explanation for other scripts will appear here as they get pushed to this repo... thanks for reading! <3
