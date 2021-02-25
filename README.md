-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Homebrew-Chex-Quest

A guide on how to install Chex Quest with homebrew on a old/new 3ds/2ds.

**DISCLAIMER:**

If this breaks your 3ds/2ds, kills your Nintendogs, or starts global thermonuclear war (in SimCity of course), do not blame me. You have been warned. If you break your device and blame me, I will point at you and laugh.  

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## FAQ:

Why would you do this?

- I was trying to find out if it was possible online, and couldn't find anything.  When I grabbed PrBoom3ds, and DSDoom, I remembered that Chex Quest was based on Doom 2's engine, so I compiled a giant guide for this.  

Did you come up with all this?

- I came up with the procedure, not the software.  

When I go the the Mediafire link, and I download the .zip file, I get a virus warning.

 - This is normal, just keep the file anyway, and continue with the guide.  False positives can happen.  

I want to play Doom 2, and Chex Quest, can I do this without needing to change the file names each time I want to play either of them?

 - I am not quite sure, I do not think you can unless the development on DSDoom continues, and the custom wads section is completely built.  Each time you want to launch them, I think you need to re-name them to "doom2.wad.  

I want to do this on my Nintendo Switch, or other device, would I be able to do this?

 - It may be possible, ~~but I have never tested it on any other device other than my 2DS~~ I have tested it on my SNES Classic, and it works on that, but that is not covered in this guide.  I am still not sure if it would work on Nintendo Switch or not.  It *may* be possible if there is PrBoom, or some other Doom engine for the platform.  

I don't want to softmod/hardmod my device, can I still do this?

 - No, due to the fact that you cannot just download PrBoom3ds/DSDoom from the Nintendo Store.  

I have an Original 3DS/2DS, does the game work/run well on it?

 - Actually the Original 3DS/2DS are the only 2 systems that I have tested!  I need someone to help me test the New 3DS/2DS, and yes, it runs just fine.  

Do I need a specific brand of SD card?

 - I just used the one that came with my 2DS, I don't think you need anything specific.  

When I try to launch doom2.wad, I just get errors, no game launches...

 - Try to read the error first, and try to see if you understand it.  If that doesn't work, then try to be sure that you have all the files that are required for this, and that chex.wad is named "doom2.wad".  

I get a "Exception Error" when I try to startup PrBoom3ds/DSDoom, or when I try to launch Chex Quest, why is this?

 - I noticed that this happens very rarely when you have a lower-end device, or a **very** old 3DS/2DS.  Try again, and see if it launches, if you still get the error, it may just be that your device isn't powerful enough.  

I want to run Chex Quest 3 on my 3DS/2DS, can I do this?

 - No.  Chex Quest 3 is a PWAD, while Chex Quest is an IWAD.  If you are not sure what a PWAD or an IWAD is, I can explain that here:
     - PWAD - Short for Patch Wad are Patches to original IWADs, can be **much** smaller than an IWAD, and can include very little of the original game.  
     - IWAD - short for Internal Wad are the full file themself, they are *normally* quite a bit bigger than a PWAD, and include all of the game files. 

How big of an SD Card does this require?  

 - I use the 4GB one that was in the 2DS when I got it.  I'd recommend **at least** 2GB for one.  

I want to do this, but I don't want to wipe the data off of my 3DS/2DS's SD Card.  

 - You do not need to wipe the data, you just need to create folders, and add some files.  

Will I be banned for doing this?

 - On a Original 3DS/2DS, No.  I am not sure about a New 3DS/2DS, but on a Nintendo Switch, you will most likely be banned for this (***Do not blame me if you get banned, you made a choice***).  

I need additional help, where can I go?

 - Join my discord server for this: https://discord.gg/VDbfe3pd.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Prerequisites

CFW with Homebrew (I use Luma3ds)

To test if you have CFW hold down the start button while turning on the console, if you get a GM9 window, you're good to go!

If nothing popped up, and you just booted normally, follow this guide: https://3ds.hacks.guide/get-started - **PLEASE READ EVERY STEP IN THE GUIDE THORUOGHLY, AND I'D RECOMMED THIS VIDEO GUIDE - thttps://www.youtube.com/watch?v=miVDKgInzyg**

## Needed Files

Download this zip archive:
https://www.mediafire.com/file/9gxho8jrp0xtcw3/chex.zip/file

Download PrBoom3ds:
https://github.com/elhobbs/prboom3ds/releases

Download the .3dsx and .smdh files

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Installation

### PrBoom3ds

Install PrBoom3ds:

Put the .3dsx, smdh, and the prboom.wad (prboom.wad from the .zip file that we downloaded in the beginning) files in /3ds/prboom3ds

Launch the Homebrew application, and there should be a new entry for "PrBoom3ds"

### Chex Quest

Install Chex Quest:

Put the chex.wad file in /3ds/prboom3ds

Rename chex.wad to doom2.wad, and launch prboom3ds from the homebrew menu!

You should now be in Chex Quest!  If you're not... Please make sure you followed this whole thing all the way through.  

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

#### NOTES:

* You can use PrBoom3ds, or DSDoom [SVN] (I use both).  
* ~~I am not sure if Chex Quest 3 works, but I will test it soon~~ Chex Quest 3 doesn't work, nor does Chex Quest 2 work. (chex2.wad & chex3.wad are PWADS, while chex.wad is a IWAD so that's why it works.)  
* Thank me for getting it running on 3ds/2ds, but not for the program it runs on, that was all elhobbs. (https://www.github.com/elhobbs)  
* You can use DSDoom works as well, just put in "doom2.wad" (chex.wad) into the folder where wads go in DSDoom.  

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

PrBoom vs. DSDoom SVN - A Comparison

**DSDoom SVN**

* Pros 
     
     Can have dual screen mode.  

     Second screen can display a map, console, or nothing.
     
     

* Cons
     
     Uses Doom sound, not Chex Quest sounds.  

     Have to select "doom2.wad" from a selection list of wads on every launch.  

     Requires a separate launcher called TWilightMenu++ (not going through that because that is outside the scope of this).  
     
     There *is* a "Custom" wad option in the wad selection menu, but it doesn't work.  
     
     Treats the top screen as the aspect ratio of a DS screen.
     
     Hasn't been in development since Jun 1, 2014.

https://drive.google.com/file/d/0B5PbaEZg8neXWGZMTldWQ2w1RW8/edit
     
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**PrBoom3ds**

* Pros

     Uses Chex Quest sounds.  

     Launches through Homebrew Launcher (which I have gotten many more things to work on Homebrew than TWilightMenu++).  
     
     Uses Fullscreen on the top screen.
     
     Latest version dates to Dec 21, 2019.
     
* Cons

     Dual screen, but just a virtual keyboard on the bottom.  
     
     Have to select "doom2.wad" from a list of wad files.  
     
https://github.com/elhobbs/prboom3ds/releases
     
     
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

If you need any help, go to the FAQ at the top, and see if that answers your question.  

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Bugs:

* Unknown?
        
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**My Homebrew setup:**

Hardware:
* Original 2DS (And yes, Chex Quest runs well on an Original 2DS)
* Default 4GB SD Card (It was good enough for my purposes...)


Software:

* CFW - Luma3DS
* GodMode9
* boot9strap

Applications:

* FTPD - For file transfers (My SD Card reader broke)
* Homebrew Launcher
* FBI
* TWiLightMenu++

     * DSDoom

* SNES9X for 3ds
* dsx86
* VirtuaNES
* PicoDrive
* PrBoom3ds
* SM64 - Just SM64 for 3ds - Not a N64 Emulator
* DosBOX
* MGBA (I know VC exists, but I hate injecting roms into VC)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

https://www.github.com/Jarmander333/

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------
