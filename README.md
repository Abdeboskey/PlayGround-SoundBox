# ▶️Ground/SoundBox

An application that allows multiple users to access the application at once, and use browser events to trigger MidiEvents/Genarate sound with the Audio API. 

## User Stories

* When logged in, A user should be able to have friends, and start SoundBoxes (breakout rooms) with friends to have private jam sessions.
* A user can also create a public SoundBox that any online user can join.

### Big Q's:

* How do we create a centralized interface that multiple users can recieve server responses from?

* Is it possible that the serve could be the site? how can we make it so that the client's instance of the service is linked with all other instances of the service?

* What types of sound events are available to us? 

  * Can a user choose a voice?
    - You can generate different waveforms with the web audio API
    - Can we also use samples with audio nodes?
  * Can a soundBox have a set key?
  * Is there looping capability?
  * Can we map a piano keyboard onto the computer's keyboard? 
  * Can we trigger modulation events with the arrow keys or trackpad?

  * Can a user apply effects to their chosen voice? can those be toggled with key commands?

* When accessing the app on a touch screen device, can we implement some sort of Kaoss pad control interface?

* Can we also incorporate visual changes that respond to audio input/output?

## Docs for Research

### Web Audio API --->

* [MDN Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
* [Creating Visualizations of Web Audio](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API/Visualizations_with_Web_Audio_API)

### Web MIDI API --->

* [Official Web Midi API Docs?] (https://www.w3.org/TR/webmidi/)
* [Article on using MIDI to trigger web-audio events](https://medium.com/swinginc/playing-with-midi-in-javascript-b6999f2913c3)



