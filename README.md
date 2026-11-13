# 1BSD
1BSD Magtape File

I am uploading the SIMH tape for the 1BSD tar from The Unix Heritage Society, I didn't create anything included here(except the .tap file)I used the rawtap program from OpenSIMH to put the tar onto a tape, then booted Research Unix Version 7, extracted the tar onto a scratch disk using the builtin V7 tar program, then using the builtin V7 tp program I created a new MagTape file from the extracted tar and now you can put this tape into V6 Unix(it's initial target)or any UNIX with the tp program and run the installer script from the instructions included in the tar from BIll Joy.  As far as I could tell no-one had ever uploaded a workable 1BSD tape so here it is, the files it extracts are in cont.a(which the 1978 instructions explain)I am working on how to use those but this is simply the MagTape for now in SIMH format, enjoy.

Update Nov 13th, 2026

I have uploaded my backported ar.c file from 2.79BSD from TUHS servers which I had to manually add itol and mktemp functions so it would compile cleanly on stock v6 unix, so with that compiled onto V6 Unix and this magtape file 1BSD is not installable on a stock V6 Unix, haven't tested compiling everything but the cont.a files are extractable with this new ar
