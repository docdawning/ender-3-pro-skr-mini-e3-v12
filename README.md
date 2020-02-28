<H1>DocDawning's Ender 3 Pro Marlin 2.x Builds for BTT SKR Mini E3</H1>
<p>This repository exists as a basic stanging ground for me to personally keep track of what I'm running on my Ender 3 Pro, which has a BigTreeTech SRK Mini E3 Version 1.2 that I picked up from <a href="https://spool3d.ca/bigtreetech-skr-mini-e3-v1-2-control-board-with-tmc-2209-uart/">Spool3d.ca</a>.</p>

<p>I am including a copy of the source I'm using from the Marlin project, you can go look at that project <a href="https://github.com/MarlinFirmware/Marlin">here</a>.</p>

<BR />
<H2>DISCLAIMER</H2>
This is posted for my own use. Others are welcome to look at it, but know that this isn't warrantied or anything. You are responsible for whatever happens if you download this and use it. I am mindful about safety and try to do things as safely as I feasibly can, but I'm human and there may be mistakes. There may even be issues that are entirely harmless for me, but not for you. Again, I'm not responsible. There's no warranty. This is as-is.

<BR />
<H2>DOWNLOAD FIRMWARE BINARIES</H2>
<TABLE>
<TR><TD>Firmware</TD><TD>Status/Notes</TD></TR>
<TR>
	<TD><a href="https://github.com/docdawning/ender-3-pro-skr-mini-e3-v12/blob/master/Marlin-2.0.x/Marlin-bugfix-2.0.x-20200227/FIRMWARE/firmware.bin?raw=true">Marlin 2.0.x BugFix from 2020-02-27</a></TD>
	<TD><a href="https://raw.githubusercontent.com/docdawning/ender-3-pro-skr-mini-e3-v12/master/Marlin-2.0.x/Marlin-bugfix-2.0.x-20200227/notes.txt">Usable</a></TD>
</TR>
</TABLE>

<BR />
<H2>INSTALLATION</H2>
NOTE: If you don't know how to install new firmware on your SKR Mini, then this probably isn't for you at all.<BR />

1. Load firmware on SKR
2. Run M502 to reset to factory defaults
3. Run M500 to save EEPROM
4. Power cycle SKR Mini

<BR />
<H2>PROJECT GOALS</H2>
I just want to get my Ender 3 Pro working well for my use case. I like the 2209 drivers of the SRK Mini, they're so quiet, it's wonderful.

<BR />
<H2>META</H2>
<UL>
	<LI>I use <a href="https://en.wikipedia.org/wiki/ISO_8601">ISO-8601</a> date formats, because I always write numbers with the high-mangitude values towards the left and the more minute values towards the right.</LI>
	<LI>My particular Ender 3 Pro was shipped from Creality in early February 2020</LI>
</UL>
