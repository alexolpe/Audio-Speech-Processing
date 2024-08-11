# Audio and Speech Processing Projects
This repository contains the subprojects done in the class Audio and Speech Processing. The work has been done in collaboration with Eudald Brils

## Voice Activity Detector
Given a voice signal, the goal is to determine at which moments there is actually voice and at which there is only silence (or noise). These systems have various applications, such as in teleconferencing systems, speech coding systems, speech recognition, etc. The fundamental criterion for discerning whether a segment is voice or silence will be its average power. In low-noise situations, it is expected that the power of the noise will be much lower than that of the voice. Therefore, a first approach to the problem would be to calculate a threshold such that, if the power exceeds this threshold, we decide that the segment contains voice; and if it does not, we decide that it contains silence. Other criteria, such as the zero-crossing rate and the length of the silences, are also used.

| Feature/Module | Link                                                                 |
| -------------- | -------------------------------------------------------------------- |
| **Project Report**   | [Link to Project Report](https://github.com/yourusername/your-repo/tree/main/module1) |
| **Code**   | [Link to Code](https://github.com/yourusername/your-repo/tree/main/module2) |

## Pitch Detection
The goal is to design a pitch detection system based on autocorrelation. The autocorrelation of a periodic signal is itself periodic with the same period as the signal. Since every signal presents the maximum autocorrelation at the origin, by detecting the position of the second maximum, we are able to determine this period.

| Feature/Module | Link                                                                 |
| -------------- | -------------------------------------------------------------------- |
| **Project Report**   | [Link to Project Report](https://github.com/yourusername/your-repo/tree/main/module1) |
| **Code**   | [Link to Code](https://github.com/yourusername/your-repo/tree/main/module2) |

## Speaker Recognition and Verification
The objective of this project is to build a speaker recognition system and a verification recognition system. Linear Prediction Coefficients (LPC), Linear Prediction Cepstral Coefficients (LPCC) and Mel-frequency Cepstral Coefficients (MFCC) are used for feature extraction. We make a comparison of performance when using the different coefficients. Finally, a Gaussian Mixture Model is used for the speaker recognition system and for the speaker verification system.

| Feature/Module | Link                                                                 |
| -------------- | -------------------------------------------------------------------- |
| **Project Report**   | [Link to Project Report](https://github.com/yourusername/your-repo/tree/main/module1) |
| **Code**   | [Link to Code](https://github.com/yourusername/your-repo/tree/main/module2) |

## Polyphonic Musical Synthesis
This project focuses on creating a simple polyphonic musical synthesis system. We start studying MIDI messages in a simplified form and we develop a polyphonic synthesizer capable of managing multiple instruments and effects. We will implement basic instruments, such as an InstrumentDumb that produces sinusoidal sounds using a table with an ADSR envelope, and add sound effects like tremolo and vibrato. We also implement FM synthesis, which modulates the frequency of a base signal to produce more complex sounds.
| Feature/Module | Link                                                                 |
| -------------- | -------------------------------------------------------------------- |
| **Project Report**   | [Link to Project Report](https://github.com/yourusername/your-repo/tree/main/module1) |
| **Code**   | [Link to Code](https://github.com/yourusername/your-repo/tree/main/module2) |
