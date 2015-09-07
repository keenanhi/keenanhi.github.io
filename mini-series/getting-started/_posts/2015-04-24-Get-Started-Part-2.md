---
title: Get Started Part 2 - What is Digital Audio? 
layout: post
description: "An overview of the conversion of sound to digital audio"
soundcloud: "off"
cover: http://i1045.photobucket.com/albums/b459/keenanhi/Get%20Started%20Series/Signal-Chain_zpsy7fogvyi.jpg
coveralt: signal chain
caption: The famed "signal chain"
tags: analog-vs-digital microphones
---

**Contents:**

* TOC
{:toc}
<br>

###What is Digital Audio?

We live in a crazy time period where we can recreate almost any sound around us, with basically no effort! Most smartphones come preloaded with a voice memo app, giving everyone the power to record sound and play it back at a moment's notice.

Why should you care about the technical details of digital audio? Well... you want your music to sound better than [this](https://youtu.be/nLq-17yD2-Y), don't you?

Learning only a little bit of the technical know-how surrounding audio will put you miles ahead of your fellow musicians, and open your ears to so much more going on underneath the surface of the music you listen to every day.

Energy from sound waves go through an obstacle course of sorts as they make their way inside a computer in a process known as **recording**. In this article, we will follow sound energy through this obstacle course, which we call the **signal chain**, as it makes its way into a computer. Here is a block diagram with the three basic parts in the recording signal chain:

![signal chain](http://i1045.photobucket.com/albums/b459/keenanhi/Get%20Started%20Series/Signal-Chain_zpsy7fogvyi.jpg)

As you can see, we start with the acoustic sound we described in Part 1, and end with digital audio inside your computer. There are three main sections to the recording signal chain: the microphone, the analog to digital converter (or the ADC), and of course the computer.

Let's start with the bridge between the acoustic world and electrical world

###The Microphone

![microphone](http://i1045.photobucket.com/albums/b459/keenanhi/Get%20Started%20Series/Signal-Chain-Mic_zps5aedzvbp.jpg)

Microphones are a type of **transducer**, which is a device that shifts energy between different forms. In the specific case of the microphone, acoustic energy is shifted into electrical energy, so they are categorized as **Electro-acoustic transducers**. We won't go too into detail about how different microphones work, as there a few different methods by which they can convert energy between the electrical and acoustical domains. Essentially, you can think of it this way: a sound wave *pushes* on something, which in turn *pushes* on electrons, sending electrons out of the microphone in the exact same pattern that the microphone was *pushed* by the sound wave. 

Here is a ubiquoitous microphone, Shure's **SM57**:

![sm57](http://i1045.photobucket.com/albums/b459/keenanhi/Get%20Started%20Series/fig1shure-sm57-bc678035_zpsqkjv54sw.jpg) 

Sound waves come into the metal mesh in front (called a **grille**), and electrical waves come out of the back of it.

Remember how a sound wave is just air molecules vibrating back and forth? When pushed by this vibrating air, the microphone pushes electrons so that they vibrate at the same frequency of the imposing sound wave.

So if you could "hear" electrons, and put your electron-hearing-ear on the output of the microphone, you would hear all of that stuff from part one: fundamental frequencies, harmonics, loudness, etc. A piano's timbre looks the same coming into and going out of the microphone, it is just that on the input air molecules are making this shape, and on the output electrons are making this shape.

Different microphones have different characteristics (sometimes called **color**) due to the distinct mechanisms through which they convert energy. These audible characteristics stem from the fact that microphones do not pick up all frequencies of sound equally; take for example the SM57 above. Included by the manufacturer with this microphone is something called a **frequency response**, which is exactly what it sounds like: how the microphone responds to certain frequencies (and thus, how it colors the sound). You can see boosts and cuts of certain frequencies in the response below:

![sm57 frequency response](http://grahamspice.com/docs/images/Shure_SM57_freqResp.gif)

We can see from the frequency response of the SM57 that it has a relatively flat response in the mid-range, with some boosts in the high end, and a cut in the low end that gently slopes as we get lower (keen observers will note that the scale of this graph is a little weird; we will get there in Part 3, for now, don't worry about it.) Thus, microphones, just like *any part* of the signal path, act as a filter. Though filtering in microphones is subtle, it is always there, whether you like it or not.

There are also other types of transducers we can use in the place of a microphone for different types of sounds: for example, if you are recording electric guitar, you can use the pickup of the guitar, which is another type of transducer. Or, if you are recording something like a synthesizer, which outputs electronic signals only and no actual sound, you can bypass this whole stage, since you are already starting with electrons! Remember: In this first step, our goal is only to convert sound energy to electrical energy.

###The Analog to Digital Converter

![Analog to Digital Converter](http://i1045.photobucket.com/albums/b459/keenanhi/Get%20Started%20Series/Signal-Chain-ADC_zpszmk9b9kv.jpg)

Next, the signal travels to a soundcard, a mixer, or, what you are probably using to record sound: an audio interface. Each of these has something called an **Analog to Digital Converter**, or an **ADC**, which acts as a translator for your computer, which works in 0's in 1's, not electrons. The ADC basically says, "Okay, electron here, electron there... that means 110010".

The ADC is a complicated device, but is unrefutably the most important to digital recording. Don't be intimidated! We will split this part of the signal chain up a little, and explain the ADC more in depth. A lot of concepts explained for the ADC have wide-arcing implications in modern recorded music, so it is imortant to really understand how this thing works.

##### Analog vs Digital

Analog to digital conversion is *hugely important*, and not something you want to mess up. To understand a bit more of how this works, we first need to understand what **analog** and **digital** mean in the first place.

The electrons entering the ADC from the cable exist in the "real world." This is different from the 1's and 0's which exist in the "digital world". You know this; if you are watching [a live video stream of a panda] (http://nationalzoo.si.edu/animals/webcams/giant-panda.cfm), the panda is not the "real world" panda, but it is a "digital world" copy that looks just about close enough, as far as we can tell. There is no panda inside your computer (really!). We would call the panda inside your computer the "digital panda" and the panda in The Smithsonian's National Zoo the "analog panda."

When you think analog, think "real world". Think: *there is no smallest chunk*.

In the "real world" we can keep dividing space forever. If you zoomed in on the real world panda, you could zoom down to its individual hairs, and then further to the proteins making up the hair, and then down to its atoms, and even further; endlessly in fact, if you have a big enough microscope. *There is no smallest chunk*.

However, if you zoomed in on the digital world panda, you would be left with individual pixels, each with the same size, past which you cannot zoom in. In this case, each pixel represents what we call a **discrete** chunk of space, meaning a finite amount of space.

In the "real world," we can also keep dividing time, forever. A second is pretty small, but a millisecond is even smaller, and a microsecond even smaller than that. If we keep dividing time, there is *no* point at which we hit a limit. *There is no smallest chunk*.

However, if you slowed down the panda cam, which is digital, you would be left with individual frames, clicking along at a certain speed. In the digital world, these clicks represent a **discrete** chunk of time (again, a finite amount of time.)

So remember: in the digital world, *there is always a smallest chunk*, and we call these chunks discrete values.

##### Audio Quality

Space and time are two aspects of the "real world" that the digital world absolutely cannot recreate, and this turns out to be crucially important in recreating sound waves, which can get pretty darn fast, and pretty darn small, and on which you could zoom in, forever, both in space and time. In the digital world, we *need* a smallest, otherwise our computers would not be able to handle the size of the audio file. We need a discrete chunk of electrons to be our smallest chunk. Luckily, there is a point below which our ears can't hear the difference between real world audio and digital audio if this discrete chunk is small enough. Generally, the smaller you go, the higher the **quality** of the recording. In audio, we call each discrete chunk a **sample**. Thus, the more samples you have in any given time or space, the higher the objective quality of your audio.

(This is the same language we use for things like drum samples; sample just means a chunk of audio. For this discussion, however, when we use the word sample, we are refering to the *smallest* chunk. In fact, a drum sample as we normally think of it is actually made up of many, many smaller samples. This is not meant to confuse; only to clarify that the sample we are refering to is the smallest sample)

##### The Digital Waveform

Thinking about audio as a wave, as we have before, can be very helpful in understanding these two ideas. Plus, audio is usually displayed as a **waveform** in recording softwares. Take the following digital waveform of a clap I clapped:

![digital waveform](http://i1045.photobucket.com/albums/b459/keenanhi/Get%20Started%20Series/clapverb_wav_zpsb90kqnrj.jpg)

This is quite intuitive to understand, but worth explaining: At the points where the waveform is very tall, it means that the ADC recieved a big chunk of electrons, and therefore that the microphone sent a big chunk of electrons down the cable to the ADC, and *therefore* that the microphone recieved a big chunk of air molecules. In other words: something loud just happened! At the points, on the other hand, where the waveform is centered at the 0, there is no sound, as far as the ADC can tell.

Intuitively, we understand that the length of these waveforms represents "digital time." Again, if we zoom in lengthwise, the thinking is the same as zooming in time on our panda cam: we know there is a limit to our time resolution here as well. If we were to zoom in enough, there will be a point at which we could see the wave click along sample by sample, just as we saw the panda cam click by frame by frame.

Changes in height of the waveform are what we can think of "digital space." If we think back to our panda cam, the thinking is the same: we know there is a limit to this resolution. If we were to zoom in enough, there will be a point at which we could see discrete jumps in height of the audio waveform, just as we saw discrete pixels on the panda cam.

Let's dig a little bit deeper into these ideas of "digital time" and "digital space," and learn some better vocabulary for those terms:

##### Sample Rate ("Digital Time")

The ADC can't translate electrons to binary at an infinite speed; it has to go back and forth, just as you would imagine a human interpreter going back and forth between worlds in which different languages are spoken. Except this human translator goes really, *really*, fast, on the order of tens of thousands of times per second.

The speed at which the ADC can translate analog waves to digital waves is what we call its **sample rate**. If you don't have a fast enough sample rate, you start to miss those rapidly vibrating high frequencies; you start to get less total samples, and the quality of your music suffers.

Now, you would think, intuitively, that to record a given frequency, you would at least have to record at the sample rate corresponding to that frequency (to record a 300 Hz tone, for example, you would have to at least record at 300 samples per second.) However, if we put ourselves in the shoes of the ADC, we realize rather quickly why this doesn't quite work out.

Imagine you are assigned a job as an ADC, and you had to figure out the lowest sample rate you could employ to capture a 300 Hz wave.

If you tried capturing a 300 Hz wave by sampling at 300 samples per second, you would capture the values represented by the blue line on the graph below.

![300Hz sampled at 300 Hz](http://i1045.photobucket.com/albums/b459/keenanhi/Get%20Started%20Series/300_sampled_at_600_zpspmnekno4.jpg)

As you can see, the blue line, or what we captured as an ADC, never moves from 0! We have failed to capture our 300 Hz tone; we cannot see 300 Hz with a sampling frequency of 300 Hz. As far as we know, as an ADC, there is no 300 Hz wave.

Let's try again, but this time doubling the sampling frequency. Notice, we get the exact same thing:

![300Hz sampled at 600 Hz](http://i1045.photobucket.com/albums/b459/keenanhi/Get%20Started%20Series/300_sampled_at_600_zpspmnekno4.jpg)

However, as we will see, any frequency above 600 Hz we will start getting values greater than zero. Here is 601 Hz:

![300Hz sampled at 601 Hz](http://i1045.photobucket.com/albums/b459/keenanhi/Get%20Started%20Series/300_sampled_at_601_zpsca5qqbit.jpg)



You can just start to see nonzero values appearing if you look at the values highlighted by red dots.

Let's try 1200 Hz for a more clear picture:

![300Hz sampled at 1200 Hz](http://i1045.photobucket.com/albums/b459/keenanhi/Get%20Started%20Series/300_sampled_at_1200_zpssywmpkty.jpg)

And 2400 Hz:

![300Hz sampled at 2400 Hz](http://i1045.photobucket.com/albums/b459/keenanhi/Get%20Started%20Series/300_sampled_at_2400_zpspcjoufbm.jpg)

And finally let's take a ton of samples; here is 44100 Hz:

![300Hz sampled at 44100 Hz](http://i1045.photobucket.com/albums/b459/keenanhi/Get%20Started%20Series/300_sampled_at_44100_zpskmdn8yal.jpg)

Where our blue digital signal is completely overlayed on our green analog signal. As you can see, any sample rate above what we call the **nyquist rate**, which is double the rate of the highest frequency wave we are trying to capture, will give us nonzero values, and the higher we go, the better of a picture we get of said wave. Even in the case of the 601 Hz wave, we have enough nonzero points that, if we tried to sketch a sine wave that intercepted all of them, we would have a sine wave at 300 Hz. In fact, computer software is so good at making these sketches, 601 Hz will do just fine to capture a 300 Hz wave. The higher our sample rate, the higher the maximum frequency we can capture. 

It turns out, 44100 Hz (or 44.1kHz), the sampling frequency we used in the last example, is a typical sampling frequency, one that is probably used by the ADC inside of your audio interface. Why is this used? Remember from part 1: humans can only hear from 20 Hz to 20 kHz. So if we wanted to be able to capture a maximum frequency of 20 kHz, we would need a sample rate above the nyquist rate, which is in this case 40 kHz. 

44.1 kHz is well above the 40 kHz, so we can use this sample rate to record anything we can hear without error. The specifics of the number are a bit more "just because." The music industry could have picked any frequency above 40 kHz, but chose 44.1 kHz as a standard, just because.

##### Bit Depth ("Digital Space")

We know that if we zoomed into the panda cam, we would eventually reach pixels of uniform height and width. So it makes sense that if we zoomed into a waveform, we would find a similar smallest chunk. In audio, we call this smallest chunk a **bit**. Before we move on, a quick explanation of the **binary system** is in order:

The binary system is just a system of counting that is easy for computers to use. We humans use a system of counting that goes something like "0, 1, 2, 3, 4, 5, 6, 7, 8, 9". For any value above that, we shift over a decimal place and start again, "10, 11, 12, 13, 14... 21, 21, 23, 24... 31, 32, 33, 34... etc". You know how it goes from there (I hope). This is called a **base ten**, or **decimal** counting system, because we have ten different symbols that we use in representing any given value.

In contrast to this system, computers use a **base-two** counting system (which is just another word for binary), which only uses two symbols: 0 and 1. A computer counts "0, 1" and then shift over a decimal place and start again: "10, 11, 100, 101, 110, 111, 1000, 1001... etc". These are just different ways of representing the same values: 0 in binary is 0 in decimal, 1 in binary is 1 in decimal, 10 in binary is 2 in decimal, 11 in binary is 3 in decimal, 100 in binary is 4 in decimal, and so on, forever (for more on conversion information, see wikipedia: https://en.wikipedia.org/wiki/Binary_number#Counting_in_binary). 

Each digit in a base-two number, at least for a digital system like a computer, is called a **bit**, and it turns out that the number of different values we can represent in a binary number is directly related to how many bits (how many digits) it contains: specifically by raising 2 to the number of bits. So if we had a 4-bit number, we would have 2^4 = 8 values we can represent. We can count these ourselves: 000, 001, 010, 011, 100, 101, 110, 111, which, remember, represent 0 through 7 in decimal (note that here we are using **leading zeros**, which are zeros on the left hand side meant to be placeholders. These are meaningless, just as they are meaningless in base-ten, e.g. when you are writing a date: 04/01/2015 which we understand as 4/1/2015)

We need the height of our waveform to be a binary number, since we want to use it inside of a computer. So the smallest possible chunk of height is 1 bit of value 0. The second smallest chunk of height is 1 bit of value 1. Notice we cannot have a value in between 0 and 1; since we are in the digital world, and we are making a bit our smallest chunk, we have to either round up to 1 or down to 0. 

Say we had a 1-bit ADC. At any given point in time, this ADC looks at it's input (coming from the microphone) and says, "how many electrons do I have here?". Unfortunately, our ADC can only count to 1 (since 2^1 = 2 values, which, remember, represent 0 and 1 in binary). So if we know we might see, at a maximum (and this is hypothetical), 60,000 electrons, we can work within the rules of: : 

* if I see between 0 and 30,000 electrons, that means 0 
* and if I see between 30,001 and 60,000 electrons, that means 1

Which is not all that useful. If we were trying to capture a sine wave, it would look something like:

![1-bit ADC](http://i1045.photobucket.com/albums/b459/keenanhi/Get%20Started%20Series/1-bit-adc_zpsqmi7vtap.jpg)

The analog wave we are sampling (green) is a sine wave at 300 Hz, while our sampled wave (blue) doesn't quite look like a sine wave.

Now say we had a 2-bit ADC. At any given point in time, this ADC looks at it's input (coming from the microphone) and says, "how many electrons do I have here?". Now, our ADC can count to 3 (since 2^2 = 4 values, which, remember, represent 0, 1, 10, and 11 in binary). So if we know we might see, at a maximum (and this is hypothetical), 60,000 electrons, we can work within the rules of: 

* if I see 0 electrons, that means 00
* if I see between 1 and 20,000 electrons, that means 01
* if I see between 20,001 and 40,000 electrons, that means 10
* if I see between 40,001 and 60,000 electrons, that means 11

 Now we are getting somewhere a little closer to our analog wave:

![2-bit ADC](http://i1045.photobucket.com/albums/b459/keenanhi/Get%20Started%20Series/2-bit-adc_zpsoflibjdo.jpg) 
 
 (Note that here we are using the base-ten values on the y-axis, not binary)
 
 Imagine now we have a 16-bit ADC, or, if we want to learn some vocab, an ADC with a **bit-depth** of 16 bits. Now, our ADC can count to 2^16 = 65536. Now our resolution is much better; we can represent each individual electron with a bit of it's own, and even have 5536 bits left to spare. Here is what we get when we sample at that bit-depth:
 
 ![16-bit ADC](http://i1045.photobucket.com/albums/b459/keenanhi/Get%20Started%20Series/16-bit-adc_zpslxhhikfw.jpg)
 
 Finally, our blue sampled wave completely matches our green analog wave (in fact, it completely overlaps it in this picture!)
 
 Most ADC's in use today are either 16-bit or 24-bit, though they often *do not* get down to resolution as fine as one electron, or anywhere close. It turns out one electron's worth of sound from a microphone is extremely, if not impossibly difficult to hear in most realistic scenarios. In fact, ADC actually measure electrical power, which is voltage times current, but thinking about things in terms of electrons is much simpler, and will suffice for our discussions.

#### Clipping

blah blah clipping

### The Computer

![computer](http://i1045.photobucket.com/albums/b459/keenanhi/Get%20Started%20Series/Signal-Chain-comp_zpslp45indb.jpg)

Finally, we have a digital audio wave from our ADC that we can save onto our computer! To store these digital sound waves, computers typically use a user-friendly software called a **Digital Audio Workstation**, or DAW for short. There are many different types of DAWs, ranging from basic freewares such as Audacity to more advanced programs like Logic, Pro Tools, and Cubase. 

(An important thing to note moving forward is that I primarilly use Logic X, because I work on a Mac, and my experience with Logic has been better for my personal needs than alternative DAWs. But don't run away if you don't have any intention of using Logic, or don't use a Mac! I will jump through flaming hoops to make sure everything I talk about on Get Mastered is applicable accross DAWs. Unfortunately, for Logic users, this means I will refrain from specifics of logic in my general tutorials. If there is demand for it, I can make some more Logic specific tutorials down the line. Perhaps a "Working With Logic" mini-series could happen if ther's enough clammor for it...)

Moving on to Part 3, we will work exclusively inside of the computer. It is important to remember that since we are working inside of a computer *from now on, everything is digital*. If you skimmed over those big analog vs. digital concepts, it will come back to bite you later when you are dealing with some more advanced features of DAWs; make sure you understand these concepts before moving on! They are tricky, but incredibly important, and your understanding of them will put your music production skills miles ahead of 99% of musicians poking their noses around Garage Band.