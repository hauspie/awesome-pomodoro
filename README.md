Awesome Pomodoro timer
=====================

This script is a simple timer that works with the awesome window manager.
Every minutes, it displays a notification using naughty notification library.

At the end of the timer, it displays a critical notification and plays a sound using mplayer


Usage
=====
$ pomodoro [time in minutes]

If time is not given, 25 minutes is used by default.

Gotcha
======
The script uses $HOME/.pomodoro/ring.mp3 for playing the sound at the end.
The provided ring.mp3 is by Mike Koenig and under Creative Commons Licence Attribution 3.0