```
     ____________________    __ ________ __ ________________  __
    / __/ / / . / __/ . /   / // / __/ // // .  / ___/   /  \/ /
   /_  / / / __/ _//   <   / _  / _/ >   </ _  / // / / / /\  /
  /___/___/_/ /___/_/\_\  /_//_/___/__/\_\_//_/____/___/_/ /_/
          ______  ____  ______ _____________________
         / / /  \/ / / / / . // .  / . / . / __/ . /
        / / / /\  /  ^^ /   </ _  / __/ __/ _//   <
       /___/_/ /_/__/\_/_/\_\_//_/_/ /_/ /___/_/\_\

```

A utility that "unwraps" a Super Hexagon video to show an alternative
perspective:

![comparison](img/comparison.gif)

## Usage

```
> python unwrap_video.py vid/trailer.mp4
```

This will pop-up two windows, one with the original video and another with the
unwrapped video.

![screenshot](img/screenshot.jpg)

You can use the script with the following options as well:

```
--help          (show all options)
--start N       (start at frame N)
--stop N        (stop at frame N)
--dumpdir DIR   (dump all frames into the given DIR)
```

## Dependencies

* Python 2.7
* [SimpleCV](http://www.simplecv.org/) 1.3 (video processing and computer vision)
* [Pyglet](http://www.pyglet.org/) (OpenGL shaders for image transforming)

(This [link](http://help.simplecv.org/question/300/ioerror-file-not-found-while-trying-display/?answer=993#post-id-993) solved a problem with the Debian package for SimpleCV that I was having.)

## Tested Videos

This project has been tested on the following videos:

* [Super Hexagon Trailer](http://www.youtube.com/watch?v=2sz0mI_6tLQ)
* [Super Hexagon Ending](http://www.youtube.com/watch?v=cmZLrW69PwY)

(You can use [this firefox plugin](https://addons.mozilla.org/en-US/firefox/addon/download-youtube/) or [this chrome plugin](http://www.chromeextensions.org/utilities/chrome-youtube-downloader/) for downloading youtube videos for testing this script.)
