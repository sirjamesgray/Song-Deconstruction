# Song-Deconstruction
instrument detection, MIDI track reconstruction

[Original Article](https://jamiegray.net/open-source-ideas/2016/song-deconstruction-software?utm_source=github%20readme) from my site.

I'm experimenting with formatting, to see if it'd be advantageous to move all my articles from my web site to github, to make it easier for developers to discover & contribute to these projects.

Below is a rough copy-paste from the article, I will be adding pictures and formatting soon.

---

When you listen to music, you can usually recognize individual instruments. The well-trained ears of musicians can identify complex aspects of musical composition: time signature, key, acoustic effects, etc. 

Music is just vibrations. Squiggles on a line graph of [air pressure] over [time]. All known characteristics of music are borne of the human mind's aptitude for recognizing patterns.

In the same way that computer vision is positioned to soon surpass human vision, we can develop "computer hearing" software to allow us to understand music in new ways. Specifically, an interface to visualize the instrumental building blocks of songs, to reveal the science behind the magic of music. 

### Instrument Recognition

First, our analysis model must be able to identify instruments. Artificial neural networks could be trained to 'guess' which instrument made a sound, based on their training data.

Graphical representation of an instrument-recognizing probabilistic function. < % instrument probability > ex: Piano, Guitar, etc. 

One way we could train these networks would be to let the program identify patterns on its own, isolate the sounds, and ask us humans to classify the sound with text. This could be a crowdsourced effort, similar to how Google trains some of its neural networks with its "Crowdsource" app. 
instrument_name = input() asks the user for an instrument label, so the network can learn the names of the different sounds.
instrument_name = input() asks the user for an instrument label, so the network can learn the names of the different sounds.

SONG RECONSTRUCTION

After we have a program that can recognize instruments, the next engineering hurdle will be to improve the ability for the program to recreate the song. A "turing complete" robotic musician -- one that makes music that sounds like a human created it. 

Some may decry this as a dystopian "death of creativity", ushering in a future where musicians are put out of business by robots. This doesn't have to be the case. 

The purpose of the reconstruction process is to improve the ability to interpret and replicate nuance. Once that nuance is quantified, it can be visualized for us humans to make even more complex and creative musical works. 
Instrument detection and reconstruction will output musician-friendly MIDI tracks that can be imported into professional music production software.
Instrument detection and reconstruction will output musician-friendly MIDI tracks that can be imported into professional music production software.

It would probably be practical to deploy different neural networks to detect different types of patterns, since there are different scopes of patterns ranging from high-level rhythms and melodies, and low-level patterns such as specific sounds and effects. 
Different networks could be deployed to identify different pattern-levels. Screenshot taken from Workflowy, graphics made in Affinity Designer.
Different networks could be deployed to identify different pattern-levels. Screenshot taken from Workflowy, graphics made in Affinity Designer.

Let's build this. Feel free to promote your GitHub project in the comment section below.

Suggested resources: 

TensorFlow  python library for building and training neural networks. 
TensorBoard for visualizing data from TensorFlow.
if you find any related open-source projects online, share them with me and I'll put them in this list. 
Check out the video explanation of this idea, the outline on Workflowy, and feel free to join the discussion on Reddit and Twitter.
