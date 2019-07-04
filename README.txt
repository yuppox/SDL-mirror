
                         Simple DirectMedia Layer

                                  (SDL)

                                Version 2.0

---
https://www.libsdl.org/

Simple DirectMedia Layer is a cross-platform development library designed
to provide low level access to audio, keyboard, mouse, joystick, and graphics
hardware via OpenGL and Direct3D. It is used by video playback software,
emulators, and popular games including Valve's award winning catalog
and many Humble Bundle games.

More extensive documentation is available in the docs directory, starting
with README.md

Enjoy!
	Sam Lantinga				(slouken@libsdl.org)

---
NOTE:

This version of SDL includes an attempt to provide a video driver for the
Mali chipset found in Odroid SBCs. The video driver is meant to be used in a
"framebuffer" environment, which means that there is no X Windows system. It
still uses accelerated rendering via EGL and OpenGL ES 2 (GLESv2).
