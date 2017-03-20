# PlexComDelete
This is a fork of PlexComskip that removes the commercials from PVR / DVRed programs and gives you an option to remux as a different file type.

I am using like this:

./PlexComDelete.py /m1/test/Cutthroat\ Kitchen.S11E23.Split\ Happens.ts

What it does:

Takes current file, create edl with segments IDed as commercials, splits the original stream into parts omitting commercials, re-joins said parts, and can even reencode to a different file format with the same name.

This is nice on Plex if you have the space in case something goes amiss on the cutting / identifying of the commercial breaks.
