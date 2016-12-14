# Digital-Music-Techniques
UCDenver class

  I created a very basic mono FM Synthesis in Max for Live.  The patch is a Max MIDI instrument, therefore it only needs to be opened in Ableton and have a key pressed to have it be played.
  
  The "Carrier Signal" side is the main oscillator waveform that is heard when having pressed a key.  The waveform and envelope of this signal can be changed with the selection box and the 4 dials on the left side of the patch.
  The "Modulation Signal" (modulation frequency) affects the carrier signal and alters its frequency through changes made in the middle section.
  
  The Signal Multiplier dial located in the top-middle of the patch changes the ratio of the modulation frequency that will eventually alter the Carrier Signal.  This frequency then becomes assigned to a determined waveform (sine, saw, or square) on the right side of the patch and becomes that waveform's initial frequency.   The Modulation/Timbre dial in the bottom-middle changes the timbre of that modulation signal, which is eventually multiplied with the carrier signal.
  The Modulation Signal envelope dials on the right side of the patch determines how long the modulation takes to kick in and how long it lasts.
  
  A plot of the resulting waveform is shown to see how different waveforms, ratios, timbre, and envelopes affect the characteristics of another waveform with its own envelope.
  
  A master gain slider is also provided on the left to easily change the loudness of the resulting sounds.
