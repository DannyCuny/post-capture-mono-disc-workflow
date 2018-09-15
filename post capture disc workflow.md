# Post-capture mono disc workflow.
  
## Overview
Audio Preservation Master files of mono, lateral-cut analog discs (shellac, vinyl, lacquer, etc.) are produced by transfering the disc's analog signal via the phono pre-amp's "stereo" mode, converting the signal to a digital bitstream, and capturing the bitstream as a two-channel file.  This method produces discrete signals from the disc's left and right groove walls, and allows restorers the opportunity to perform specific digital signal processes --including phase correction-- which would be impossible had the disc been transfered in the "mono" mode.  

Because the pre-amp's "stereo" mode also produces signal generated from verticle motion of the cartridge sylus (in a lateral-cut disc, this is mostly rumble and surface noise from the bottom of the disc groove, with little or none of the recording's intended signal), these Presrvation Master files require addtional processing to produce their Presentation (access) Masters. The following workflow explains that process, and: 

  * will sum the file's left and right groove wall signals  
  * optimize the signal generated from the lateral motion of the stylus     
  * eliminate the signal generated from the vertical motion of the stylus  
  * reduce or eliminate phase problems  
  * will render a file with a mono soundfield.

The Digital Audio Workstation (DAW) illustrations in the following workflow description have been taken from Adobe Audition CC, 10.1.1.11  

## Workflow

1)	Load the Preservation Master file into the DAW

2)	Run the phase correction process on the Preservation Master file and export as a copy, as needed.    

3)	Put file’s Left channel in Track 1 of the DAW's multi-track editor:  

* pan Track 1's mixer strip to the center, or 0, position  
* lower Track 1's mixer strip to -3db.

4)	Put the file’s Right channel in Track 2 of the DAW's multi-track editor:

* pan Track 2's mixer strip to the center, or 0, position  
* lower Track 2's mixer strip to -3db.  
  
  
---
*Example: file with the Left and Right channels revealed*

<p align="center"><img src="MonoDisc_1.JPG" /></p>


    
*Example: file's Right channel in Track 1 and its Left channel in Track 2 of a multitrack session*    

![tracks 1 and 2](MonoDisc_2a.jpg). 

---
5)	Reverse the polarity on the Track 1's mixer strip; leave the polarity of Track 2's mixer strip in the normal position.  

---

*Example: mixer strips with adjustments made to the polarity, panning, and level*   


<p align="center"><img src="MonoDisc_3.JPG" /></p>.  

---

6)	Play the file and nudge Track 1's fader gain, plus or minus tenths of a dB at a time, until the resulting output of Track 1 and 2 is as near to null as possible [Ideally, this this adjustment will completely cancel the lateral component of the signal, leaving only the vertical component –which is mostly rumble, noise, and some clicks and pops].

7)	Return the polarity to the normal position on Track 1's mixer strip.  Leave Track 1's fader at the setting made above, in step 6. [Ideally, this new balance will completely eliminate the vertical component of the signal, and optimize the lateral component of the signal –which is the intended signal].

8)	Render a new mono file from the mix

9)	Continue with other restoration signal processes (de-click, eq, etc.), as needed
