# 500kB HYBRID GRAND PIANO for FM-1 (WIP)

A piano firmware for the **M-VAVE FM-1**: a work in progress, and you are welcome to try it.
The goal was to prove that it can be squeezed to 500kB.

When you try it - press Play to hear the demo song.

<img width="500" alt="image" src="https://github.com/user-attachments/assets/cc4570d2-fb75-4528-a98e-0d64c3ac66fb" />

**[Install](https://fartypants.github.io/fm1-piano/hybrid/nightly/install/)** (Chrome or Edge, also Chrome on Android or
Chromebook; the FM-1 on USB) ·

**[Try it in the browser](https://fartypants.github.io/fm1-piano/hybrid/nightly/emu/)** ·

**[Manual](https://fartypants.github.io/fm1-piano/hybrid/nightly/manual/)**

Installing replaces what is on your FM-1. The installer's **"Back to the stock firmware"** puts M-VAVE's own firmware
back (or use M-VAVE's updater, M-UPGRADE).

## Try it in the browser

The [emulator](https://fartypants.github.io/fm1-piano/hybrid/nightly/emu/) runs the same firmware code as the FM-1,
with its screen, knobs, buttons and keys, and the sound, in Chrome or Edge, so you can hear it before installing
anything.

- **Play** with the mouse or touch (click the keys and buttons), with a MIDI keyboard connected to the computer (allow
  MIDI when asked; CC 64 is the sustain pedal), or from the computer's keyboard: white keys Q–I and A–K, black keys
  1–0 and -, Enter the sustain pedal (held), Z / X octave down / up, Esc HOME.
- **The demo:** press PLAY to hear Chopin's Étude Op. 10 No. 1.
- The knobs: drag one up or down, or scroll over it; from the keyboard, Tab to it and ↑ ↓.

## What it is

A *hybrid* piano: combines sampled piano (the hammer, the strings'
onset, the soundboard), and continues as a modelled tail, so notes ring and decay
naturally without storing seconds of samples for every key. The recordings are the Kawai grand from the
[Versilian Community Sample Library](https://github.com/sgossner/VCSL) (CC0).

- **The piano:** one velocity layer shaped by a velocity colour filter, dampers
  with their measured damping, the sustain pedal (MIDI CC 64 or REC on the FM-1).
- **Presets:** 12 factory sounds (Studio Grand, Concert Hall, Intimate, Pop Bright, Old Upright, Felt Piano, New Age,
  Mellow, Old Bar, Prepared Bolt, Rubber, Ambient) and 8 user slots. Nothing is saved until you press SAVE.
- **Shaping:** touch (hardness, velocity curve, attack, brightness, onset, hammer), strings (sustain, detune, stretch,
  damper, prepared-piano partials, tail), body (bass, mid, treble, stereo width, tape wobble).
- **Effects:** a reverb with five types (Plate, Room, Studio, Hall, Church) and a ping-pong delay.
- **Scale and key:** light the keys of a scale, mute the notes outside it, or snap them to the nearest scale note
  (15 scales).
- **A demo:** PLAY on any page plays Chopin's Étude Op. 10 No. 1 through the engine.
- Plays from the FM-1's keys and from MIDI in (USB or the TRS jack); up to 16 voices.

## Status

Unfinished and changing often: sounds, presets and the pages may change between builds, and a new build may reset
your saved settings or turn the entire instrument into a kazoo. 

## Licences

- The KAWAII piano recordings: VCSL, CC0.
- The compression: [QOA](https://github.com/phoboslab/qoa) by Dominic Szablewski, MIT.
