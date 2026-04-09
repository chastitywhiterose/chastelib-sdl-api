# chastelib SDL API

This repository began as an extension of chastelib, which was my own routines for writing text and integers to standard output. The library was working well for terminal programs but then I got a wild idea!

What if instead of a Linux terminal, the functions output text to an SDL window using my favorite bitmap font?

After a month of working on it on my off nights, I managed to create a working example program that exceeded my original vision. I had complete control over the color and scale of the text I drew.

But there was a problem! Should I base it on SDL2 which I had the most experience with when I made chastetris? Or should I go with the modern SDL3?

I couldn't decide because I appreciate all libraries new and old. Therefore I made 3 separate versions of the same program which each function in the exact same way using the code matching that version of the SDL API.

Because I worked on this code so much, I wanted to have a separate repository for it so that others can easily navigate it and use it for projects they have in mind.

<https://github.com/chastitywhiterose/chastelib-sdl-api>

The basic idea is that it will remain simple but allow making small text based games except compatible with modern graphical PCs and consoles (such as games made for Steam Deck). If you find it useful, please let me know!
