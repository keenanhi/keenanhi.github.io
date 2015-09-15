---
subtitle: Get Started Part 3
title: What is Mixing?
layout: post
description: "An overview of the tools and techniques common to modern mixing"
soundcloud: "off"
cover: http://i1045.photobucket.com/albums/b459/keenanhi/Screen%20Shot%202015-09-03%20at%203.36.47%20PM_zps5ojmcegn.png
coveralt: faders
cover-blur: http://i1045.photobucket.com/albums/b459/keenanhi/Screen%20Shot%202015-09-03%20at%203.36.47%20PM_zpsucy7hkr3.png
color: "text-light"
caption: Some digital faders, used to control levels
tags: automation compression EQ reverb depth

---

**Contents:**

* TOC
{:toc}
<br>

###What is Mixing?

Now that we've learned all of the ins and outs of digital audio, we can get to the fun stuff: mixing and mastering. In this part of the Get Started series, we will talk about the mixing process. 

**Mixing**, in it's simplest definition, is altering the volume of sounds, and adding them all together. Think of a sound engineer at a live show: they are often being yelled at to "turn up the vocals" or "turn down the electric guitar" or "turn down the electric guitar even more please." Turning different instruments "up and down," often called changing the **levels** of each instrument, is the most basic form of mixing. 

Mixing has become more advanced throughout history, as a result of inventions such as **equalization**, **stereo music**, artificial **reverberation**, and other effects. Due to these advances, modern mixing is also concerned with three other important characteristics of individual sounds within a song: tone, placement in "virtual space," and effects.

Often in a DAW, we will have various tools we can apply to a track, software we call **plugins**. In this article, we will also go through some of the tools used to achieve different sounds within a song. In addition to plugins, we often have other DAW controls available, including some for sound editing.

In this part of Get Started, we will discuss the four fundamental aspects of mixing (levels, tone, placement, and effects) and the tools used to craft them in greater detail. We will also go through some of the basic DAW controls, including editing.
 
###Levels

The most basic of the four aspects of mixing is **levels**. The level of a track within a mix is simply the volume of that track.

Typically, in a DAW, each track has what's called a **fader**, which is a slider that dictates the volume of the track. A bunch of faders from Logic X are pictured below:

<img src="http://i1045.photobucket.com/albums/b459/keenanhi/Screen%20Shot%202015-09-03%20at%203.36.47%20PM_zps5ojmcegn.png" alt="faders" width="70%">

<!--![faders](http://i1045.photobucket.com/albums/b459/keenanhi/Screen%20Shot%202015-09-03%20at%203.36.47%20PM_zps5ojmcegn.png)-->

The faders are those grey sliders placed vertically on each track.

Levels are important in their own right, as their relation to each other often define the hierarchy of instruments in the mix. Levels also play an important part of simulating a sound coming from a far distance, as we will see later.

A typical situation that arises during mixing is that a certain instrument may need to be louder or quieter depending on the part of the song. For example, maybe the kick drum need a little boost during the chorus. Another typical situation is that certain parts of the instrument's sound may need to be louder or quieter than other parts of the instruments sound. For example, maybe the kick drum is too loud *riiiight* when the batter head hits the drum head, but is a little too quiet when it is resonating.

(as a little side note: I will always be saying  *kick drum* and not *bass drum*, since the latter terminology is sometimes confusing when used in the same discussion as *bass guitar*, which happens quite frequently).

The two different types of situations call for two different solutions. In our first situation, we can solve the problem with what is called **automation**, while in the second situation, we can solve the problem with what is called **compression**. In the next two sections, we will briefly go over these two tool in our mixing arsenal.

####Automation

**Automation** is used to change the value of a paramter throughout a song. In this case, we can use automation to change the level of a certain track in different sections of a song, or even during certain words, as is common with vocal tracks. 

Here is an arbitrary example of automation on a kick drum track.

<img src="http://i1045.photobucket.com/albums/b459/keenanhi/Screen%20Shot%202015-09-04%20at%2012.09.39%20PM_zpsyvg5ykft.png" alt="automation" width="70%">

<!--![automation](http://i1045.photobucket.com/albums/b459/keenanhi/Screen%20Shot%202015-09-04%20at%2012.09.39%20PM_zpsyvg5ykft.png)
-->
As you can see, as the song plays from left to right, the level of the track will change from -5.9 dB, to +1.0 dB, to other values.

In most DAWs, you have the ability to draw in different values over the course of a song with a pencil tool (producing shapes known as **envelopes**). This is what I did to quickly make the automation points in the above picture.

Most DAWs also have the functionality to record parameter changes made by the mix engineer as the song plays. When levels in particular are changed during the course of a song by an engineer monitoring the mix, it is typically called **riding the fader**, for pretty obvious reasongs.

Sometimes, though, we have changes we want to make to a sounds' level that are too fast for us to catch with our hands or a pencil tool, or changes that keep repeating every snare hit, say. It would be very difficult or tedious to use automations to fix these sorts of problems, so for those we turn to **compression**.

####Compression

**Compression** is a tool we can use to "even out" certain parts of a sound. An easy example for this is our kick drum example, where we might want to dull down the **attack**, where by attack we mean beginning of the sound. 

Here's a compressor that has a nice visualization of some common controls:

<img src="http://i1045.photobucket.com/albums/b459/keenanhi/Screen%20Shot%202015-09-04%20at%2012.06.48%20PM_zpskc0htcaq.png" alt="compressor" width="70%">

<!--![compressor](http://i1045.photobucket.com/albums/b459/keenanhi/Screen%20Shot%202015-09-04%20at%2012.06.48%20PM_zpskc0htcaq.png)-->

All of the bolded vocab to follow can be found in the second left-most column of this particular compressor (which even has more controls than we will touch upon here).

Compressors work by scaling down the level of a track as it gets louder. So if a compressor had what's often called a **ratio** control set to "2:1", it would compress the signal down so it only ever gets half as loud as it normally would. Similarly, a 3:1 ratio would squash the sound a third of it's normal volume. You get the idea: the higher the ratio, the more compressed the sound. 

Compressors also often have a **threshhold** control, which controls the point at which the compressor starts working. If, say, we wanted only the sound spike that happens during the attack of the kick drum to be compressed, and everything underneat that to remain the same, we would set our threshhold between the spike or peak value, but above the resonance of the kick drum after it has been hit.

The x-axis (horizontal axis) of our pictured compressor represents the input volume of the compressor during any given moment, and the y-axis represents the output volume. This compressor has a ratio of more than 20:1, which is visualized clearly by the virtually flat output above its theshhold of -40 dB. 

You can also tell from this graph that the input can go from -100 dB to 0 dB, while the output can never go above -40 dB. These ranges are called the **dynamic range** of a track. the reason why a compressor is named as it is is because it is compressing the dynamic range.

Sometimes we want to bring the compressed track back up in volume, since compression often makes our track sound quieter. We can do this by adding **makeup gain**. If we give this compressor 40 dB of makeup gain, our graph looks like this:

<img src="http://i1045.photobucket.com/albums/b459/keenanhi/Screen%20Shot%202015-09-06%20at%201.04.52%20PM_zpshvqlszvs.png" alt="makeup gain" width="70%">

<!--![makeup gain](http://i1045.photobucket.com/albums/b459/keenanhi/Screen%20Shot%202015-09-06%20at%201.04.52%20PM_zpshvqlszvs.png)-->

Now, our dynamic range is the same size, it has just moved from -100 dB through -40 dB to -60 dB through 0 dB. This, in effect, makes our track sound louder than it originally did, because it will never fall below -60 dB (as opposed to our input sound, which still has the dynamic range of -100 dB through 0 dB). Some compressors automatically apply makeup gain, so these compressors, counterintuitively, automatically make a sound louder, because they are both compressing and adding makeup gain.

Compressors often also have **attack** and **release** controls. Imagine the compressor is "squeezing" the sound, as a person might squeeze a stress ball. The attack control dictates how quickly the compressor "squeezes" the sound, and the release control dictates how quickly the compressor "let's go" of the sound.

Compressors are a very tricky thing to hear, especially when they are used subtley, as they ofoten are (it should be noted that a 20:1 ratio as seen is the example above is an exageration of typical values; usually we will have a ratio between 1:2 and 1:5). A huge part of mixing and mastering is grasping exactly how changing these controls changes a sound, and a compressor is one of your two most important tools as a mixing engineer.

####Limiters, Expanders, and Multi-Band Compressors

Compressors also come in a few different flavors. A standard compressor acts as we have discribed above, but their are other types of compressors with slight differences. 

A **limiter** for instance is a compressor with ratio and threshhold controls tied together: as the threshhold decreases, the ratio increases. A popular limiter is shown below:

<img src="http://i1045.photobucket.com/albums/b459/keenanhi/Screen%20Shot%202015-09-04%20at%2012.08.59%20PM_zps4ljuzahk.png" alt="limiter" width="70%">

<!--![limiter](http://i1045.photobucket.com/albums/b459/keenanhi/Screen%20Shot%202015-09-04%20at%2012.08.59%20PM_zps4ljuzahk.png)
-->
An **expander** is the opposite of a compressor; it boosts the sound above a certain threshhold, essentially a compressor with a ratio between 0 and 1.

There are also multi-band compressors, which are compressors that work differently depending on the frequency of the sound. A **de-esser** is a type of multi-band compressor tailored to work on frequencies sqpecific to **sybilant** sounds produced by human speech (think of an "s" sound).

###Tone and EQ

In addition to compression, **equalization** (EQ), a tool with which you can change the tone of an instrument, is one of the most important tools with mixing and mastering. 

EQ is used to turn up and down certain frequencies, and often uses several user-defined filters to do so (remember filters?). These filters can be different shapes, which will be outlined in the following sections.

The two most basic, and proabably most used filters, are the **high pass filter** (HPF) and **low pass filter** (LPF). As their name might suggest, they each pass certain frequencies through them untouched while filtering out other frequencies. A HPF filters out the highs, while a LPF filters out the low. Confusingly, these filters are also sometimes called low *cut* and high *cut* filters, respectively. Just take a moment to think about what the terms mean, and this alternate terminology is not too confusing.

HPFs and LPFs have a parameter called **slope** (sometimes called **roll-off**) which dictates how steep the filters are. They also have a **cutoff frequency** control which ditates where they start passing highs or lows.

Below is a picture of a HPF, with a slope of 24 dB/octave and a cutoff frquency of 79 Hz:

<img src="http://i1045.photobucket.com/albums/b459/keenanhi/Screen%20Shot%202015-09-04%20at%2012.07.15%20PM_zpsjlq4nz6c.png" alt="HPF" width="70%">

And next is a picture of a LPF, with a slope of 24 dB/octave and a cutoff frquency of 7 kHz:

<img src="http://i1045.photobucket.com/albums/b459/keenanhi/Screen%20Shot%202015-09-04%20at%2012.07.43%20PM_zpsdornclmf.png" alt="LPF" width="70%">

<!--![LPF](http://i1045.photobucket.com/albums/b459/keenanhi/Screen%20Shot%202015-09-04%20at%2012.07.43%20PM_zpsdornclmf.png)-->

In both of these visualizations, we can see our EQ "greying out" (i.e. filtering) frequencies below and above their cutoff frequencies (respectively).

Another type of filter is a **bell filter**, which is named because of it's bell shape. Bell filters can be turned up or down with a **gain** control, and also often have a **Q** control, which dictates how broad the filter is. Bell filters usually have a lower Q value, meaning they are broader in nature. Bell filters are often used gently, and are usually quite subtle.

Below is a picture of an EQ using a bell filter with a gain of +9 dB and a Q value of 0.3 (located below the gain value in this picture). It is located at the frequency 1040 Hz:

<img src="http://i1045.photobucket.com/albums/b459/keenanhi/Screen%20Shot%202015-09-04%20at%2012.07.57%20PM_zpslpdmsxya.png" alt="bell filter" width="70%">

<!--![bell filter](http://i1045.photobucket.com/albums/b459/keenanhi/Screen%20Shot%202015-09-04%20at%2012.07.57%20PM_zpslpdmsxya.png)-->

As you can see, with a low Q value, we get a broad, bell shape. In this case, as opposed to the HPF and LPF, the grey region of frequencies are boosted.

Alternatively, if a filter has a high Q value, meaning it is very narrow, and is being used to cut (i.e. the gain value is negative), we usually call this a **notch** figure, aptly named because we are notching out a certain small band of frequencies. Usually a notch filter can be used effectively to cut out a particular frequency in a very transparent way. 

Below is a notch filter at the same frequency, with a gain of -24 dB and a Q value of 2.1:

<img src="http://i1045.photobucket.com/albums/b459/keenanhi/Screen%20Shot%202015-09-04%20at%2012.08.19%20PM_zpsxmjjzmrm.png" alt="notch filter" width="70%">

<!--![notch filter](http://i1045.photobucket.com/albums/b459/keenanhi/Screen%20Shot%202015-09-04%20at%2012.08.19%20PM_zpsxmjjzmrm.png)-->

In this case, again, the grey frequencies are cut.

Since a filter with such a high Q value is rarely used to boost frequencies, we don't really have a name for that case. Call it a "generally bad sounding filter"  if you would like.

As should be clear, most changes made to a sound via EQ are subtle or transparent in nature, though they can be  more heavy handed; it all depends on the context and desired result! However, sometimes more radical tonal changes are desired, and for those we often resort to effects, which we will discuss later.

###Placement

When we listen to well produced music in a quiet listening environment, it often sounds like we, the listener, have been placed inside of an actual space, a room where we can hear, for example, a piano to our left, a tambourine to our right and far away, and a singer front and center, sounding very close.

Placing sounds within this virtual environment is one of the jobs good mix engineers will spend a lot of time and thought on. Often, this can give an okay mix a serious wow-factor, and (of course) is quite difficult to do effectively. An ability to recreate a realistic virtual environment is often what separates the good mix engineers from the great.

The placement of an instrument within the virtual space of a mix is based off of two factors: the **panning** of the instrument, or its angle from the listener (left, right, center, and anywhere in between), and the **depth** of the instrument, or how far away the instrument sounds.

Usually, a good mix engineer will create a hierarchy of instruments within a mix, having the main parts be front, center, and close, with the supporting parts being panned harder and sound as if they are coming from farther away. Things like lead vocals, kick drum, snare drum, and bass will typically be front, center, and close, while maybe a supporting harmony vocal, hi hat, or guitar might be skewed to one side, and far back. Again though: this all depends on the individual song! These are just some enormously common occurences, *not hard and fast rules*.

####Reverb

Panning is usually a rather simple to control; most DAWs have a built in panning knob on each track. Depth however, isn't quite that easy, but there are a few tools at our disposal. When creating a sense of depth, mix engineers often employ, in conjunction with other tricks, a tool known as reverberation, or **reverb** for short. 

Reverberation in a room is any sound wave you hear that does not come directly from the source of that sound. Often in addition to the direct sound wave, we will hear sound waves that started at the source, bounced off of a wall, or two, or three, or thirteen, and then arrived at your ear. All this extra sound is what we call reverb (sometimes thought of as echo, but there is a difference. Reverb is often much more difficult to discern compared to reverb. Technically, acoustic echo is a certain type of reverb).

Reverb can be added artificially in most DAWs using anything from basic to hugely computational algorithms, and often the quality is dicernable to more experienced ears. Real reverb can also be recorded directly, often with great results; think of the sense of depth you get listening to a well done live recording of a concert.

Here is an example of a great reverb engine that comes bundled with Logic X:

<img src="http://i1045.photobucket.com/albums/b459/keenanhi/Screen%20Shot%202015-09-04%20at%2012.10.23%20PM_zpslj3m0e2n.png" alt="reverb" width="70%">

<!--![reverb](http://i1045.photobucket.com/albums/b459/keenanhi/Screen%20Shot%202015-09-04%20at%2012.10.23%20PM_zpslj3m0e2n.png)-->

A reverb plugin, like most effects plugins, has a **wet** and a **dry** fader (located on the top right of this picture), used to control the reverb (the wet signal) and the original, direct sound (the dry signal). In addition to this, reverbs have some other common controls including **pre-delay**, which sets a time delay between the wet a dry signals.

We won't get too much more into *how* to go about creating a sense of space in your mix here: I have to save some of those details for future series! (which, have I mentioned, you will miss out on if you don't sign up for the mailing list in the sidebar?).

###Effects

Now finally, everything else: effects. Almost any change in sound that is not as subtle as the above techniques can be classified as an effect (at least, that is *my* definition). 

Any of the tools we talked about earlier (automation, compression, EQ, and reverb) can be used as effects if they are heavy handed or radical enough. More common effects include delay, distortion, chorus, flanging, and pitch shifting, but we won't go into them much here (again, we'll go into them in future series if you're not missing out on those!). They're the kind of things that most of you have tinkered with, and if you haven't, they're loads of fun, and usually come prepackaged with most DAWs. Go turn some knobs an listen to what happens! 

###DAW Controls

In addition to tools that alter sound, a lot of DAWS have added controls for ease of workflow. A couple of these you may have noticed in the earlier picture of the Logic X faders, notably the buttons labeled M and S

<img src="http://i1045.photobucket.com/albums/b459/keenanhi/Screen%20Shot%202015-09-03%20at%203.36.47%20PM_zps5ojmcegn.png" alt="faders" width="70%">

<!--![faders](http://i1045.photobucket.com/albums/b459/keenanhi/Screen%20Shot%202015-09-03%20at%203.36.47%20PM_zps5ojmcegn.png)-->

These stand for **mute** and **solo**, respectively. Muting a track does exactly what you would expect, and can be used to completely remove the track from the mix. Soloing a track temporarily mutes all other tracks, so that a mix engineer can listen closely to just the track being solo'd. This can be very useful for fine tuning individual sounds within a mix.

####Editing

Sometimes a mix engineer might want to align certain tracks, remove squeaks, breaths, or thuds, or pick and choose the best parts from multiple takes. All of these features are luckilly included in most DAWs as editing controls.

Usually this can be done in what is often called the **workspace** of the DAW, pictured below:

<img src="http://i1045.photobucket.com/albums/b459/keenanhi/Screen%20Shot%202015-09-06%20at%201.46.36%20PM_zpsa5mn2bcf.png" alt="workspace" width="70%">

<!--![workspace](http://i1045.photobucket.com/albums/b459/keenanhi/Screen%20Shot%202015-09-06%20at%201.46.36%20PM_zpsa5mn2bcf.png)-->

In the workspace, we can see a layout of particular **regions** (chunks of recorded audio) within a song. Each horizontal row represents one track, often containing color coded regions of audio for different sections of a song. These regions can be moved around, if, say, two drum tracks aren't quite lined up because of some recording delay between the two tracks.

Regions can also be **cut**, meaning the region is sliced into two separate regions. This is often done by cutting at the **playhead**, which is the white vertical line in the above picture which indicates where in the song we are. If we hit play, the song will start playing wherever the playhead lies, and will follow along through the song.

Editing is often a manual process, and is helpful for fixing things that we can't fix with plugins.

###The Finished Mix

Finally, we have our levels set, our tone sounding nice, our mix has a sense of space, we've added some tasteful effects, and we've edited out all of our extraneous noises. Now what?

Once a mix is finalized,  it is **bounced** (exported) to a single audio file. Usually, however, this single file can sound a bit quieter than songs we normally listen to, and may not sound as cohesive as we may like. Luckilly, we can fix these problems through **mastering**, which we will talk about in [the final part of the Get Started Series](/mini-series/getting-started/Get-Started-Part-4/)

