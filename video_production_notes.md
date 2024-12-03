# Video tutorial guide

1. Use OBS-studio, it's pretty easy
2. In settings. In Output->Recording. Quality is "High Quality, medium File size". Format is ".mkv". Encoder "Hardware (NVENC, H.264)" and audio encoder as AAC. Audio should be sample rate of 48Khz. Video "base" and "output" resolutions should both be 1920x1080
3. When setting a scene with audio capture ensure only one audio capture device, your microphone, is enabled (you may have to mute the default mic/aux). 
4. When recording a take ensure you start with a pause of 5 seconds before first speak. This captures a sample of the audio floor which can be used for denoising later.
5. At the end of each take pause for 5 of so seconds to give some footage of the desktop/final shot that can help in making cuts/edits
6. Make your cursor nice and big so that it can be followed in the screen capture. If uinsg OBS "display capture" source ensure "capture cursor" is selected. If recording in Win 10 then ensure "Capture Method" is "windows 10 (1903 and up)"
7. Each tutorial should be stand alone and should not assume someone has watched another tutorial. Though you can refer people to other tutorials so you don't have to repeat yourself. For instance if a job runs PSIPRED you don't have to explain all of PSIPRED just mention there is a PSIPRED tutorial.
8. Walk through the input page and show how to submit a job, explain each extra option if there are any
9. If the job has a long runtime (over 1 min) then do seperate takes to cover the input and the results. I'll then splice them together with an appropriate cut/transition.
10. On the results page walk through each area of the results. If there is a table describe what each column means and if there is a link follow the link and show the user what is at the end of the link and explain why. Also provide some interpretation, what does this result see mean in context. That is, the test sequence is mostly a bacteriarhodopsin, so that prior knowledge is useful in assessing if the result is good of bad. If there are any gotchas in interpreting the results mention those. After that explain the downloads panel and each of the links. Download each of the files. Then using a text editor open each file in turn and explain what is in there, making reference to the results page.

Have a look at one or two of the existing tutorials to get an idea.

## Productions Thoughts

I generally adlib the content and don't use a script. I would say it takes 2 - 20 takes to get a bit down. Sometimes you flub it immediately, sometimes you're 5 minutes in and you get tongue tied all of a sudden. Sometimes you do a great take and 20 minutes later you realise you totally forgot to mention something. It's amazingly annoying.

You could do lots more shorter segments and they can be edited together if you're struggling and I certainly find it is very hard to cleanly ad-lib more than 5mins of content. However you do it, make sure that all captures are clearly/obviously named so their sequence is clear (i.e. 01_psipred_inputs.mkv, 02_psipred_results.mkv). If you're going to do lots of small captures then you need to be careful where your mouse pointer is on screen for continuity reasons. Also better to edit things end-to-end if possible. That is, I'd rather not cut short segements (errors) out of longer takes if possible as I'd like to reduce the number of transitions/cuts. Ideally there should be just one cut in between submitting the job and describing the results. So if you make and error in a 5min section better to just do a whole new take.

For the miking yourself, if you're facing the mic then having something soft or curtain-y behind you is great if possible. A pop screen for a mic is great to avoid sibilants and plossives coming throught too much, though having the mic at right angles to you and talking across the front of it works too. The closer to the mic you are the deeper, richer and nicer your voice will sound.
