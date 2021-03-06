# Video Art

This is a collection of video art resources focused on glitching, weirding, or otherwise destroying things.

-----

## Datamoshing

### Avidemux
[Avidemux](http://avidemux.sourceforge.net/) is a free tool commonly used for datamoshing. You can also do basic video editing with it, though many people edit the original videos in some other software (e.g. Premiere).

Here are some good introductions to Avidemux:
- [How to datamosh videos | Datamoshing](http://datamoshing.com/2016/06/26/how-to-datamosh-videos/)
- [TUTORIAL Make Video Glitch Art: How to Datamosh, in Plain English - Art! - Glitchet Forum](https://forum.glitchet.com/t/tutorial-make-video-glitch-art-how-to-datamosh-in-plain-english/36)
- [HOW TO DATAMOSH | Asap Mob - Yamborghini High Music Video Effect  (Premiere Pro & Avidemux Tutorial) - YouTube](https://www.youtube.com/watch?v=UKmhWnFnlh4).

Other handy tools to have are [VLC](https://www.videolan.org/vlc/index.html) for viewing and converting a variety of video files and [ffmpeg](https://www.ffmpeg.org/) as a general command-line video utility.

Many people report that Avidemux doesn't work as well for datamoshing on newer versions of OS X (I don't know about Windows or Linux). Some people recommend using a different operating system (e.g. with [VirtualBox](https://www.virtualbox.org/)).

I tried downloading Avidemux 2.5.4 based on these instructions — [TUTORIAL How to install avidemux for datamoshing on Mac OS X - Art! - Glitchet Forum](http://forum.glitchet.com/t/tutorial-how-to-install-avidemux-for-datamoshing-on-mac-os-x/33)  — but it wouldn't load on my system (OSX Mojave).

That said, Avidemux 2.7.1 seems to be stable on a fully updated Mac. Here are instructions for using a later version (> 2.7) of Avidemux: [Datamoshing using Avidemux 2.7.0 | Antonio Roberts](https://www.hellocatfood.com/datamoshing-using-avidemux-2-7-0/). Using these settings, I was able to get some glitch effects, but they were hit or miss. Your mileage may vary.

### Other tools
This is a comprehensive list of resources for making glitch art: [Glitchet: Art Resources](http://www.glitchet.com/resources)

#### Scripts
These are command-line tools for datamoshing and glitching videos:
- [Making mosh-ups: automated datamoshing from multiple video sources](https://parkerhiggins.net/2017/07/making-mosh-ups-automated-datamoshing-from-multiple-video-sources/)
- [GitHub - happyhorseskull/you-can-datamosh-on-linux: it's a script that makes datamoshing with python fun and easy](https://github.com/happyhorseskull/you-can-datamosh-on-linux)
- [GitHub - grampajoe/Autodatamosh: Perl script that automatically datamoshes MPEG4-encoded AVI videos.](https://github.com/grampajoe/Autodatamosh)
- [GitHub - amgadani/Datamosh-python: Datamoshing scripts written in python](https://github.com/amgadani/Datamosh-python)
- [GitHub - fand/node-aviglitch: A node.js porting of aviglitch rubygem by ucnv.](https://github.com/fand/node-aviglitch)
- [GitHub - ucnv/aviglitch: A Ruby library to destroy your AVI files.](https://github.com/ucnv/aviglitch)
- [GitHub - wayspurrchen/byebyte: Destroys your files (on purpose).](https://github.com/wayspurrchen/byebyte)

#### Audacity
Someone used Audacity successfully to do datamoshing - [Datamosh'd a screenshot with Audacity, came out pretty vibrant. : datamoshing](https://www.reddit.com/r/datamoshing/comments/9s0los/datamoshd_a_screenshot_with_audacity_came_out/).

### General resources
- [Datamoshing](http://datamoshing.com/)
- [Glitchet Forum](http://forum.glitchet.com/)
- [Topic: glitch-art · GitHub](https://github.com/topics/glitch-art)
- [r/datamoshing](https://www.reddit.com/r/datamoshing/)
- [r/glitch_art](https://www.reddit.com/r/glitch_art/)

#### How-tos
- [I know the _how_ of datamoshing but I can't get a specific effect to work. : datamoshing](https://www.reddit.com/r/datamoshing/comments/ajiih4/i_know_the_how_of_datamoshing_but_i_cant_get_a/)

-----

## Neural Networks
I'm just starting to dabble here:
- [Dreaming Neural Nets](https://www.reddit.com/r/deepdream/)
- [GitHub - manuelruder/artistic-videos: Torch implementation for the paper "Artistic style transfer for videos"](https://github.com/manuelruder/artistic-videos)
- [How Artists Can Install Neural Networks to Make Art](https://www.jackalope.tech/how-artists-can-set-up-their-own-neural-network-part-2-neural-network-install/)
- [Home · jcjohnson/neural-style Wiki · GitHub](https://github.com/jcjohnson/neural-style/wiki)
- [GitHub - jcjohnson/neural-style: Torch implementation of neural style algorithm](https://github.com/jcjohnson/neural-style)
- [r/deepdream](https://www.reddit.com/r/deepdream/)
- [r/deepstyle](https://www.reddit.com/r/deepstyle/)

-----

## Utilities

- [ffmpeg](https://www.ffmpeg.org/) is a great general command-line video utility.
  - [Advice on how to split a video file into chunks using ffmpeg](https://unix.stackexchange.com/questions/1670/how-can-i-use-ffmpeg-to-split-mpeg-video-into-10-minute-chunks)
- [HandBrake](https://handbrake.fr/) is a tool for converting video from nearly any format to a selection of modern, widely supported codecs.

-----

## Fixing things

Once you start destroying videos, you'll find that it can be hard to put them back together again, especially if you want to post them on social media.

Here are some suggestions to fix broken video files. Your mileage may vary — you can follow these steps in sequence or do them separately.

- Duplicate the clip and save the filename with an .avi extension. MacOS will give you a warning, but it's fine.
- Open the AVI file in VLC and convert it to MP4. When you do this, you may want to keep the original audio track, which you can specify in the customization options. This will output an M4V file.
- Use ffmpeg to convert the M4V file to MP4.
- Upload the file to YouTube, let it process, and then download it.
