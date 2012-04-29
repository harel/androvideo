Androvideo - Harel Malka 2009
http://www.harelmalka.com

Note: this is an old script I created and used on an HTC Magic / Android 1.6. For new phones this is not really needed.

A bash script to help convert video files for usage in the android based HTC G1/Magic 
handsets. I've done this script for myself mainly, so it assumes you're using a debian
based distro for the setup portion of the script. If you don't have apt, you'll have 
to do the leg work and get all the pre-equisites sorted out yourself.
The conversion is pretty straight forward but requires the h263 decode/encode libs
and ffmpeg to be compiled against them. When you perform the setup portion the script
will *attempt* to do all for you, but this is only an attempt. 

What is supposed to happen is:

  * Get all build dependencies for ffmpeg via apt.
  * Gets a few libs ffmpeg will need, subversion, checkinstall and build-essentials
  * Downloads the amr shared libs from http://www.penguin.cz/~utx/amr and attempts to compile/install
  * Gets latest ffmpeg from svn and attempts to compile/install with the amr libs included
  * Get rid of all downloaded files and compiled pre-install crap

I could not have done this without the very good help from these resources:

http://www.linuxquestions.org/questions/linux-mobile-81/androidg1-and-video-converted-via-ffmpeg-h263-687163/

http://po-ru.com/diary/up-to-date-ffmpeg-on-ubuntu-hardy/

http://tldp.org/LDP/abs/html/ 

http://www.penguin.cz/~utx/amr

