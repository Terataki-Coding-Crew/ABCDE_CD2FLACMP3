# Utility to rip CDs to both FLAC and 320 MP3s

### Requirements:
abcde 
lame 
eyed3 
glyrc 
imagemagick 
cdparanoia 
flac
abcde-musicbrainz-tool (to use musicbrainz for CD art and track listing etc)


### Use

run cp /etc/abcde.conf ~/.abcde.conf


Edit ~/.abcde.conf - uncomment CDDBMETHOD= and edit to CDDBMETHOD=musicbrainz,CDDB


You might also want to set PADTRACKS=y
to help avoid problems with track listing order.


cd to target directory and run script - *Ensure CD is in the drive*



### TODO:
Error handling


