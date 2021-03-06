---
layout: archive
title: "Why Polyphonic Instruments?"
date: 2016-01-10T11:39:03-04:00
modified:
excerpt: "Remember the step from the mono to poly synthesizer? 
The step from the monophonic to polyphonic guitar is not quite the same but of a similar order!
We think its the next step to take, and technology is available, the music will follow"
tags: []
image: light_synth.jpg
  feature:
  teaser:
---

<b>What do we mean by Polyphonic?</b>

Some say <i>"Hexaphonic", </i> which is only correct as long as the instrument has 6 stings, so we prefer "Polyphonic" here: 

Polyphony has its specific meaning in the music history, but the word itself simply means that there are several "sounds" and we understand several "voices" or notes. Of course this is the case for any ordinary guitar, but conventional technology treats all notes as a single sound source - which is often not in the sense of the musician! We are mainly talking about electric instruments here, but even for the accoustics: Ask any luthier whether he would not build a different guitar for each string!

In the seventies, the first instruments picked up each string and processed them separately. Here some of the possible improvements:

<b>Polyphonic Distortion </b>
For guitars, distortion is the most obvious reason to separate strings, there is no intereference between strings. The difference is huge!

<b>Polyphonic Envelope </b>
All effects which read or create an enveloppe work a lot better because it does not make sense to repeat the attack sound for all notes each time a new note is plucked. for example a monophonic touch-wah filters all strings at once, independent on which string is plucked.

<b>String Selection</b>
Once separate string signals are available we can detect the loudest, lowest and highest playd, the last attacked,,, string and give it a different sound or mute the others or whatever...

<b>GuitarSynthesizer</b>
Once pitch can be detected on each string, a polyphonic synthesizer can be driven. thats why some call a polyphonic guitar "MIDI-Guitar" although it only makes MIDI conversion possible - and much more than that!

<b>Modelling</b>
Imitation of other kinds of guitars or pickups only works well when strings are treated separately.
some of the effects immediately sound better for any kind of playing 
others allow to play new sounds with the old guitar technique
others need to be rehearsed, some need musical skills...


<div class="tiles">
{% for post in site.categories.articles %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->