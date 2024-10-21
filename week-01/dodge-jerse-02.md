# Computer Music: 2 The Acoustics and Psychoacoustics of Music

### Initial Questions
**What is the difference betwen Acoustics and Psychoacoustics**
- Acoustics model the pysical attributes of sound. Psychoacoustics model the
  human perception of sound

## 2.1 Sound and the Ear

### Initial Questions
**How does our ear turn pressure waves into perceived sound?**
- The surface of our ear drum vibrates from the sound wave hitting it.
- It passes these vibrations onto the cochlea which is filled with fluid and has
  an organ in it called the basilar membrane.
- The basilar membrane has hairs with nerves that send signals to our brain at
  the frequency of the sound.
- Loudness is determined by the intensity of the acoustic energy.

**How does our ear differ from an analog or digital recording device?**
- Microphones aren't discussed in this section, but if I remember correctly,
  the part in a microphone which vibrates in response to an acoustic wave is
  magnetic.
- The disturbances on the magnetic surface generate an electric wave in tandem
  with the magnetic field displacement (a la electromagnetism)
- So a microphone differs from an ear in the physical/biological means of how it
  transforms acoustic energy into electric energy
- Namely a microphone uses a magnetic surface while an ear uses a multi-organ
  process including organ surfaces, bones, fluids, hairs and nerves

### Notes
**Limitations of Human Hearing**
- Human hearing ranges approx. from 20 Hz to 20 kHz
- Threshold of audibility ranges from 0.00002 N/m^2 to 200 N/m^2

**Acoustic Properties and their Psychoacoustic "Analogs"**
- Frequency -> Pitch
- Amplitude -> Loudness

While the psychoacoustic "analogs" correlate to their acoustic counterparts.
Other factors may change how they are percieved. Consider for example, the
Doppler effect.

- **Intensity** is a measure of power in a sound that contacts the ear drum.
  Proportional to the square of amplitude and measured in Watts per sq. meter

- Intensity is percieved logarithmically - i.e. percieved based on the ratio
  between two values

- The **decibel** (dB) is a relative unit of measurement of ratio between two
  intensities.

- dB may also be used to reference ratio between two amplitudes, but its only
  correct if they're "measured under the same set of conditions"

- **Interesting statistic:** Conversational speech has roughly the same level of
  intensity as pianissimo (pp) loudness in an orchestra

- **Interesting statistic:** Tuning fork waveforms are nearly perfect sinusoids

- A phase comparison of two wave forms is only meaningful if they have harmonic
  frequencies (i.e. the ratio of their frequencies is an exact integer)

- More on this can be read in "Introduction to the Physics and Psychophysics
  of Music" by Juan C. Roederer. p.21

## 2.2 Pitch

**Frequency range of Human Hearing**

- While human hearing ranges 20Hz to 20kHz, the greatest acuity is in the range
  200Hz to 2000Hz.

- This range occupies 2/3 of the basilar membrane. Higher frequencies only
  occupy 1/3

- The shorter the duration of a note, the harder it is for the brain to discern
  its pitch, regardles of loudness

**Just Noticable Difference**

- The **Just Noticable Difference** (JND) is the physical limit of change in
  frequency that we can notice

- Some people speculate that the JND corresponds to the "spatial separation of
  points of stimulus" on the basilar membrane

- The JND varies with frequency level and with each person

- The statistical average JND at 100Hz is 3% and the at 2000Hz is 0.5%

- More on this can be read in "Introduction to the Physics and Psychophysics
  of Music" by Juan C. Roederer. p.23

**Beat Frequencies**

- The frequency of a beat is determined by the difference between its tones

- The pitch of a tone with beats is the average of its components

- **Mistuned consonants** is another type of beat that happens when two tones
  an octave apart are slightly out of tune

- Mistuned consonants are much harder to discern above 1500Hz

- Other beat tunings occer at perfect fourhts and fifths
  (4:3 an 3:2 respectively)

- The **limit of discrimination** is a point where the frequency difference
  between two tones is large enough that we percieve them as two different
  tones instead of the average between them

- The **critical band** is the point where the frequency difference between
  tones where the the percieved sensation transitions from **tonally rough** to
  **tonally smooth**

### Consequent Questions
**What's the difference between the limit of discrimination and the critical
band?**

- I _think_ limit of discrimination has to do with frequencies while critical
  band has to do with timbre?

### Interesting references
- Sharf, Bertram.
  "Critical Bands." _Foundations of Modern Auditory Theory_ (vol 1.). 1970

## 2.3 Musical Tuning

**Formula for equal-tempered tuning:** _I^1/N_
- Where _I_ is the "base interval" (e.g. octave is 2)
- Where _N_ is the number of subdivisions

**Non-standard tuning examples**
- D&J 5.12 discusses John Chowning's _Stria_ which uses phi (golden ratio) in
  its tuning system

## 2.4 Perception of Amplitude

The **JND** varies not only with fundamental frequency, but also with
spectral character of a sound

- For a sine tone, JND is typically 0.2  to 0.4 dB

**Threshold of Masking** is the intensity where a soft tone is no longer
audible in the presence of a louder tone

- depends greatly on frequency difference and amplitude of louder tone
- depends somewhat on the frequency of louder tone

The ear may create **aural harmonics** in a loud tone which do not exist in the
physical waveform

## 2.5 Temporal Relationships

Our ability to perceive pitch is dependent on the frequency
- we must hear a minimum number of cycles before perceiving pitch
- i.e. lower pitches take longer to hear
- e.g. 100 Hz tone must last at least 40 ms, 1000 Hz only 13 ms
- granular synthesis exploits this to use samples with shorter times

**Three primary ways of perceiving sound sequences**
1. **Coherence:** The sequnce is heard as a single "line" or "melody"

2. **Fission:** When the sequence is played with a fast enough tempo, but not
   too fast, it can be perceived as two or more separate lines or melodies
   playing together

3. **Fusion:** When the sequence is played with a tempo at audible rate - the
   sequnces is perceived as a waveform

- The size of the interval between tones affects the tempo boundary between
  coherence and fission

### Interesting References
- Backus, John. _The Acoustical Foundations of Music_ (2nd ed.). 1977

- Van Noorden, L. A. P. S.
  "Temporal Coherence in the Preception of Tone Sequences." 1975

## 2.6 Classical Theory of Timbre

**Spectral description of sound**
- Equivalent descriptor to a wave form
  - measures intensity vs frequency as opposed to amplitude vs time
- **Spectral envelope** the distribution pattern of intensity across frequency 
  - i.e. the spectral envelope _is_ a sound's intensity-frequency graph

**Frequency band limitations**
- both acoustic and synthesized tones are **band-limited** so that frequencies
  above a certain point don't have enough energy to be recognized

- the **bandwidth** of a sound is the width of the frequency region where that
  contain "significant" components of frequency

- the **rolloff** of a sound characterizes how the intensity diminishes with
  frequency

**How spectral envelopes affect how we differentiate timbres**
- Our perception of timbral similarity is largely based on absolute frequency
  bands

- two tones with different fundamental frequencies but with the
  same energy distribuition over partials often have different timbres

  - e.g. 50 Hz triangle wave has most energy from 50 t0 450 Hz, while a 250 Hz
    triangle wave has most energy from 450 to 2250 Hz

- A **formant** is an energy peak in an absolute frequency region
  - two tones with similar timbres will have similar formant structures

**How acoustic bodies affect formant structures**

- when traveling through a **resonating system** the amplitudes of partials
  in specific frequency regions will be emphasized

- different tones on the same instrument will have similar timbres because
  the same frequency regions are emphasized

**Formant peaks and the critical band**

- Adjacent harmonics above the fifth fall in the same critical band - I think
  meaning that we can't distinguish the difference in their frequencies

- thus the intensity of the harmonics above the fifth only add to the intensity
  of the formant peak

### Consequent questions
- Does the band-limit of a sound depend only on the band limit of our ears?
  How much of a role does masking play if any?

### Interesting references
**Discussion of spectral envelope of musical instruments**
- Matthews, M. And Pierce, J. "Harmonic and Non-harmonic Partials." 1980
- Hutchins, C. M. "Bowed Instruments and Music Acoustics." 1980

## 2.7 Modern Studies of Timbre

- In contrast to the standard Helmholz envelope model, in natural sounds,
  partials usually have distinct envelopes

- the envelope shape is likely dependent on the parital - in Grey's study on
  trumpet tones, the envelope shapes look to form a 3D surface

**Onset asynchrony** is the difference in attack times among partials
- McAdams study shows that if onset asynchrony exceed 30-70 ms, spectral
  components orm a weaker perception of fusion into single sound

- study by Rudolph Rasch shows asynchrony improves ability to percieve chords

### Consequent questions
**Can the envelopes of partials of different timbres be interpolated into
another timbre to create unique tones?**

- Apparently John Chowning does this in _Phonee_! 
- Another composer A. Wayne Shawson does similar operations in _Colors_

### Interesting references

**Use of th FFT to analyze sound***
- Risset, Jean-Claude. _Computer Study of Trumpet Tones_. 1966

- Moorer, James A.
  "On the Segmentation of Continuous Musical Sound by Digital Computer." 1975

- Morrill, Dexter. "Trumpet Algorithms for Computer Composition." 1977

- Moorer, J. A. and Grey, J. M
  "Lexicon of Analyzed Tones (Part 1: A violin Tone)." 1977

- Moorer, J. A. and Grey, J. M
  "Lexicon of Analyzed Tones (Part 2: Clarinet and Oboe Tones)." 1977

- Moorer, J. A. and Grey, J. M
  "Lexicon of Analyzed Tones (Part 3: The Trumpet)." 1977

**Studies in onset asynchrony**
- Grey, John M. and Moorer, J. A.
  "Perceptual Evaluations of Synthesized Musical Instrument Tones." 1978

- McAdams, Steven.
  "Spectral Fusion and the Creation of Auditory Images." 1978

- Rash, Rudolph.
  "Aspects of Perception and Performance of Polyphoic Music." 1978

## 2.8 Music Cognition

- three components of music common across all cultures
  1. use of discrete pitch intervals
  2. octave equivalence
  3. presence of four to seven focal pitches in an octave

- the contents of a "musical stream" may be lost if too many components are
  changed at once
