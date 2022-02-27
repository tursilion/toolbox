19890601

I wrote this when I got my first disk system - it's a simple collection of disk utilities written in Extended BASIC.

This makes use of Barry Traver's XXB extensions, which are autoloaded by the LOAD program. After getting to the READY prompt, enter RUN "DSK1.TOOLBOX" to get into the program.

It only works with single-sided, single density (90k) floppies, so it's really more curiousity than anything else. It's also fairly slow, due to be written in XB.

Note: this program worked when I last used it /32 years ago/, but I take no responsibility for it now. Classic99 won't like a lot of the utilities, and it doesn't expect errors in certain operations.

Once it starts, press a key to get past the title page.

0) Sector editor - you are first shown this summary of the keypresses:

	S) Search for text - search disk for text (must wait for the search to finish)\
	T) Enter text - ((not sure this works correctly))\
	H) Enter hex - ((not sure this works correctly))\
	=) Next sector - load the next sector from the disk\
	/) Last sector - load the previous sector from the disk\
	R) Read sector - enter a specific sector to read\
	W) Write sector - write out the sector back to disk\
	P) Dump to Printer - print the sector to the active printer\
	9) Back to main menu
	
	.) Show from >80 to >FF\
	,) Show from >00 to >7F
	
1) Disk Map - shows the location of files on the disk. Any key to exit.

2) Sector copy - copy a disk by sectors - ((not sure this works))

3) Catalog disk - show a listing of the current disk

4) Set printer/disk specs - lets you enter a printer and the disk index to operate on

5) Delete files ((not sure this works))

6) Protect/Unprotect files - intended to control the protection bit. ((not sure this works))

7) Rename files - change the name of a file ((not sure this works correctly))

8) Rename Disk - change the name of a disk ((not sure this works correctly))

9) Quit - use this to exit the program

