Here's a probably way too comprehensive list of the emulators I personally recommend for most popular systems, mostly from experience  
(Also all of these are assuming you actually have a decent computer, if you got a spoiled potato some of these might not run well for you)

---

# Nintendo Home Consoles


## NES - Mesen (https://www.mesen.ca)

Technically a multi-system emulator, but it's probably the best one for the NES, not sure how well it does the other systems.  
Has about all that you'd expect from an emulator, also with texture pack support and a basic netplay system.  
If you're not a fan of it, there's some good alternatives, like puNES, though honestly, any modern emulator should be good enough for what most people want.  

## SNES - ares/bsnes (https://ares-emu.net)

Putting these both together as these are pretty similar, with ares being multi-system (as the heir to higan) and bsnes being more focused on the SNES,  
with the former being updated more in general compared to the latter. (Mostly will be taking about ares past this.)  
Has a ton of features, including some more-or-less exclusive to it, like Run Ahead.  

## N64 - simple64/ares(?) (https://simple64.github.io)

While this has been the one I've generally used before, if you care accuracy it might be better checking ares.  
Regardless, still your best bet outside of ares, and is also a lot more out-of-the-box compared to most other emulators for this console.  
Has generally what you'd expect, and also has a dedicated netplay system (a.k.a you don't need to portforward to use it).  

## GameCube/Wii - Dolphin (https://dolphin-emu.org)

Grouping these together since they share the same answer... do I even need to say what it is?  
Easily one of the most mature out of the ones listed here, the only thing I could really say is PLEASE use the latest releases, do not bother with 5.0.   
Also has arguably the best netplay system listed here, and combined with Wii VC and the integrated mGBA,  
it might be worth using it over other solutions to play with other people.  

## Wii U - Cemu (https://cemu.info)

Pretty much the only real solution for Wii U, but it is good. 
Has what you'd expect, plus built-in online support (requires a dumped Wii U NAND), and amiibo support.  
Also has texture packs in the form of Graphics packs, which also support mods and cheats.  

## Switch - Ryujinx/Suyu

Unfortunately, it's been harder to find it ever since the shutdown,  
but if you want a version of it that's still getting updated, check out ryujinx-mirror.  
https://github.com/ryujinx-mirror/ryujinx  
If you're looking for an Android solution, it seems like you're gonna have to go to Suyu for that.  
https://git.suyu.dev/suyu/suyu/releases  

---

# Sega Home Consoles


## Master System (& GG) - Genesis Plus GX/Snepulator/ares/BlastEm(?) (https://snepulator.net/main.html)

I'm honestly not too familiar when it comes to SMS/GG, mostly have been a Kega Fusion user when it comes to them,  
but you should probably not be using that in the BIG 2024.  
Also worth mentioning that GPGX is only on PC as a libretro core, so unfortunately you can't get it standalone.  
Ares might be your best bet for that then, or BlastEm, but I'm not sure honestly.  

## Genesis/Mega Drive - BlastEm/Genesis Plus GX (https://www.retrodev.com/blastem/nightlies)

Sorta similar story to the Master System, except BlastEm is definitely worth using, don't bother with 0.6.2 though, use the nightly.  
Genesis Plus GX is also good too, as always.  
(By the way, while not listed, if you care about the Sega CD/32X, you can check out either [PicoDrive](https://github.com/notaz/picodrive) or ares.)  

## Saturn - Mednafen (https://mednafen.github.io)

Surprisingly this is the first mention of Mednafen here, and this is a showcase of one of its greater cores.  
However, it's worth mentioning it is kinda annoying to use for most people since it is a CLI program,  
however thankfully there are frontends for it, so check out [Mednaffe](https://github.com/AmatCoder/mednaffe) or [MedGui Reborn](https://github.com/Speedvicio/MedGuiReborn).  
It also seems to have a decent netplay system, though it does require portfowarding though.  

## Dreamcast - Flycast (https://github.com/flyinghead/flycast)

A couple of years ago, there might've still been an argument to use something like DEmul for NAOMI stuff, but as of late, this is basically the main real option.  
Features pretty much everything you need, plus built-in networking, and if you're interested in netplay, check out [Flycast Dojo](https://github.com/blueminder/flycast-dojo).  
I mean, you can play Rhythm Tengoku on it... do I need say more?  

---

# Sony Home Consoles


## PlayStation 1 - DuckStation (https://github.com/stenzek/duckstation)

I'm not too experienced when it comes to PSX, but it seems this is the winner.
Has everything you would probably need, and there isn't really much missing here.
Though even with all that, Mednafen is still an option, and is probably your best bet for netplay. 

## PlayStation 2 - PCSX2 (https://pcsx2.net)

There are technically other options for this, like Play!, but this is really the only one worth using.  
There isn't really much else to say, other than having a similar featureset to DuckStation.  
At least you get to see this [cutie](https://x.com/fancyaltaccount/status/1830457721436397807) on your monitor screen.  

## PlayStation 3 - RPCS3 (https://rpcs3.net)

Similar to Cemu where it's basically the only actual option.  
I don't do much with PS3, so I can't really add any more.  

---

# Microsoft Home Consoles


## (Original) Xbox - xemu (https://xemu.app)

Seems to work with most games, and has a basic featureset.  
I wish I could say more, but I don't really play Xbox stuff.  

## Xbox 360 - Xenia (https://xenia.jp)

Not worth repeating what I said above.  
There's also a netplay/systemlink fork if you're interested for some reason.  
https://github.com/AdrianCassar/xenia-canary/releases  

---

# Handheld Consoles  
#### (Grouping all of this into one since there aren't that many)  


## Game Boy (Color) - [bgb](http://bgb.bircd.org)/SameBoy/mGBA (https://sameboy.github.io)

There's a lot of "not bad" choices when it comes to the GB, but these two are probably the best.  
I still generally use mGBA though since it's good enough and I already use it for other things (foreshadowing).  
Also even though these are the most accurate ones, they would probably still do fine on a potato lol.  

## Game Boy Advance - mGBA (https://mgba.io)

Oh would you look at that, here it is.  
There's always the (not) good ol' VBA and VBA-M, but mGBA basically makes them irrelevant.  
mGBA doesn't have any kind of netplay built-in yet, but you could easily just do it through Dolphin.  
(The emulation wiki also says you can use Ryujinx with NSO too but I'm not sure how that works.)  

## Nintendo DS - melonDS (https://melonds.kuribo64.net)

Similar to mGBA for GBA, this basically makes everything else irrelevant, lol.  
Still a bit barren feature-wise, but still good overall.  
Doesn't have any direct netplay yet, but can play online if setup right.  

## PlayStation Portable - PPSSPP (https://www.ppsspp.org)

More similar to Cemu and PCSX2 where it's the only real option.   
Got a lot of shit to be honest, and I bet even an iPod Nano could probably run this fine.  

## Nintendo 3DS - Citra (https://github.com/PabloMK7/citra)

Similar situation as Ryujinx, but there's a more clear solution.  
If you're interested, you could check some of the other forks,  
like [lime3DS](https://github.com/Lime3DS/Lime3DS), which kinda does its own thing, and [Mandarine](https://github.com/mandarine3ds/mandarine), which is more of a MMJ type of fork.  

---

# Thank you for reading!  
I don't expect anyone to actually read all the way down, but if you did, thanks!  
If you're wondering, this was originally made as a message for a Discord server, but it hit the Nitro character limit, so I decided to make this a page instead.  
And if this page gets popular enough or whatever, I might consider adding a Misc. section for consoles not really relevant enough to get their own category.  
Lastly, I might rewrite some of these sections at a later point, they're pretty bare right now, and of course I'll be updating this as stuff gets updated and released.  
Anyways, good day!
