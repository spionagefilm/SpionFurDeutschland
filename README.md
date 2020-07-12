# SpionFurDeutschland
Assist with translating a 1950's German film, 'Spion fur Deutschland' to English subtitles (1 hour 36 minutes long movie)

If you have the ability and the time, why not help with a movie subtitle transcription and translation project!

After reading 'Agent 146: The True Story of a Nazi Spy in America' (https://www.amazon.com/gp/product/0312307977/), about a Nazi spy who was dropped off in America to spy on the Manhattan Project to develop the Atomic Bomb, I was fascinated.
The book is an autobiography by Erich Gimpel, the aforementioned spy.  More about his story is on Wikipedia at https://en.wikipedia.org/wiki/Erich_Gimpel

When I learned a movie about this little-known WWII spy episode had been made in Germany in 1956, called 'Spion für Deutschland', I immediately ordered a copy from
https://www.amazon.com/gp/product/B015EW74HU

The only problem was, it was in German, and no subtitles were available.  I really wanted to watch this movie!
I had taken a couple of years of high school German- not great but a start.  And I also saw this as a way to expand my meager language skills somewhat. 
I resolved to do my best to learn what I could to translate it and to use all the resources I could.  But I realized I was a bit over my head from the beginning.

I started by using an online AI based transcription service, http://sonix.ai.  For $20 (with some credit left over), the result was not too bad, a start, and also it was directly able to output a movie subtitle file.  I realized that a lot of dialogue was being missed, especially that which was more indistinct or in the background.
I did a pass using my basic German understanding along with Google Translate to add to the transcription and translate what was there.  The result was watchable, but a bit frustratingly dumb.

At the same time, I became aware of AI-based colorization technology, specifically DeOldify  https://github.com/jantic/DeOldify
Great! why not translate and colorize this movie.

It takes a lot of processing power but the results were interesting. I translated and colorized the movie trailer as a test project.  It took an overnight run just to process the trailer using the default google collab projects.
I learned much about how to set up DeOldify, with the goal of setting up a bootable USB drive to boot my normally Windows machine into Linux to do the processing on my own machine.  Eventually I was successful (subject of a future post).
I also had just built a new gaming machine for my son, which happened to have an Nvidia 2070 Super. It turned out to be very good at processing colorization.
Initial results were it took about 14 hours to colorize 3 minutes of video on my laptop with GTX 1070.  Still, I broke up the movie into 3 minute chunks and was ready to process it that way. However, once the 2070 Super was online and everything was working, it took 4 hours 41 minutes to process the entire hour and a half long movie (8.6 frames per second colorization). The result is not perfect, but I think this technology will improve over time.

Here is the trailer (click CC to enable subtitles).
https://www.youtube.com/watch?v=K8JIcB4DfWU


How to help:

I am using Subtitle Workshop to edit the subtitles and scrub through the movie.  It allows you to keep both languages, transcription and translation in the same file.
It uses an '.stp' extension file, available in the Files section of this project.
http://subworkshop.sourceforge.net/download.php

VLC can play the subtitled version (http://www.videolan.org).  It uses an .srt file. I have included these also.

You need a github account (free).
Please feel free to contribute even the slightest of improvements. You can do this by editing the file directly (possible but maybe not recommended as you can screw things up fairly easily), or by downloading Subtitle Workshop and working directly with the movie and project files in their user interface (git will track all the additions and changes by contributor).

For now due to copyright issues I don't want to post the video file publicly. If someone contacts me at spionagefilm@gmail.com I will send them a link to the video file.
Better yet if you buy a copy of the film.
I also want it to be clear that I have no commercial interest in this, this is purely a curious little rabbit hole of a passion project.

I will trust Git to handle managing multiple contributors. It occurred to try and break it into pieces and have each contributor select an unused piece to work on, but I'm not sure of a way to do that or if it's really necessary or a good idea.  If anyone has suggestions please feel free to get in touch through git or at spionagefilm@gmail.com.

And lastly, thanks very much for your help.

Where to go from here:

I expect that like me, people who participate in this project at most want to watch the movie with english subtitles, or want to show it to someone (or are sufficiently interested otherwise for some reason to participate). It's open for discussion what to do with this after that. Possibly we could get in touch with the publisher eventually and offer it to them in case they want to add subtitles and even colorization to the DVD. There may also be sites where the subtitles could be submitted. Open for any and all constructive suggestions.

thanks again.


