# Yamaha-PSS-290-Soundfont
Pretty accurate sampled representation of Yamaha PortsSound PSS-290 "Toy Keyboard"/2 operator FM synthesizer as soundfont (.sf2).

# Changelog

## Version 1.0.0 (initial release)
- extends the PSS-290's limited capabilities (fixed velocity, low polyphony on complex presets)
- all of the 100 (not General MIDI compatible) sound presets are covered
  - one sample/octave
  - currently only octaves available without pitch shifing covered
- bank 0 attempts to map the PSS-290's 100 presets to 128 soundfont presets
  - (somewhat) General MIDI compliant
  - some creative liberties taken
- bank 1 contains direkt representations of the PSS-290's 100 presets ("00 PIANO" to "99 SINE WAVE")
- some limitations/inaccuracies include
  - pitch-independent LFOs not captured well (will be pitches regardless because of limited sample count)
  - envelopes more complex than just ADSR not properly captured
- all unique PCM drum samples (from the rhythms/styles) were captured but
  - no drum set preset(s) (yet to figure out best way to do so)
  - some drum samples included on bank 0
 
