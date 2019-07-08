﻿# TwitchStreamMock

To stream to the application, use a platform, such as OBS. 

In the settings menu, navigate to the Stream tab, and input into the URL section: rtmp://localhost/live. 

For the stream key, it will require the created stream's id key, which can be found in the address bar when the stream is selected in 
the Steam List (ex: http://localhost:3000/streams/1, the 1 is the id key). 

Create a new scene, then create 2 sources, an Audio Input Capture and a Display Capture. 

For the Audio Input Capture, set the device to your preferred microphone.

For the Display Capture, set the display to your current main monitor. 

To go live, just click the Go Live button.

When finished, click the End Stream button.
