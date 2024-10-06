# Computer Music: 1 Fundamentals of Computer Music

### Initial Questions

**What are the fundamentals of Computer music?**
- how a computer is used in various forms of an audio system

**How are the fundamentals of Computer music useful to me as a composer and as a programmer?**
- understanding of what data and algorithms allow a musician to define a
  composition

## 1.4 The Use of a Computer in Audio Systems

### Initial Questions

**What qualifies as an audio system?**

- in the context of this chapter, an audio system is any audio signal system 
  which takes an input and produces an output

**What roles can a computer take in audio systems?**

- recording, synthesis and playback
- processing and analysis

**How does a user interact or not interact with a computer in an audio system?**

- recording and playback might have minimal user interface, but synthesis has
  unbounded, limited only by creativity

- processing and analysis are defined by the specifc use cases

### Notes

- audio is stored digitally by recording the numeric values that represent the
  voltage in the audio signal

- In turn, voltage in the audio signal represents pressure in the audio wave

- I/O devices convert signal between Digital and Analog (D/A vs A/D)

- Low-pass filters are necessary before converting A/D and after converting
  D/A to prevent unwanted components in the sound (discussed in chpt 3)

- Uses of computer in audio system:
  - **Digital Recording:** recording an analog signal into digital signal
  - **Digital Playback:** reading digital signal into audio signal
  - **Signal Processing:** modifies digital signal before sending it somewhere
  - **Signal Analyzer:** determine characteristics of an audio signal
  - **Digital Synthesis:** generating a digital audio signal

### Consequent Questions

**What are some interesting ways a signal can be processed?**
- isolating timbres in complex audio
- modulation (chpt 4), filtering (chpt 6), reverb (chpt 10)

**What characteristics might be useful to analyze from an audio signal?**
- acoustic charactersitcis of speech
- characteristics can be used as basis for digital synthesis and undestanding
  psychoacoustics

## 1.5 Software for Computer Music

### 1.5A An Overview

Forms of music software:
- sound synthesis
- modification of synthesized or sampled sound
- assistance with composition for acoustic instruments
- computer performance of composed music

Computer Music Composition architecture:
- musician determines sound palette with _instruments_
- instruments may be modified by its parameters
- can be designed to generate simultaneous parts and long evolving sounds
- a _score_ is a sequence of musical events that describe when and how
  instruments may play

### 1.5B Examples of Computer Music Languages

Computer composition software process:
- Musician input is in instrument and score definition
- sound generation and score processing are done by the computer
- compiled and run to produce sound
