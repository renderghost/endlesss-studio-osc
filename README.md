# :control_knobs: Control **Endlesss Studio** with your iPad and TouchOSC

I'm a huge fan of [Endlesss](https://endlesss.fm). I play a lot on my phone, but I needed a dedicated controller to get the same experience on desktop. I've been interested in [TouchOSC](https://hexler.net/touchosc) for a while, and thought this would make a fun project to *kill two birds with one stone*.

:no_mobile_phones: I made this for use with an iPad Pro 12.9". This controller has a [Creative Commons license](https://github.com/renderghost/endlesss-studio-osc/blob/main/LICENSE) so feel free to resize it to your device, or do whatever else you want with it. Just don't sell it. I'd love to see what you come up with.

If you have ideas for changes, please :bulb: [start a discussion](https://github.com/renderghost/endlesss-studio-osc/discussions)

![endless-studio-osc-1_0.jpeg](https://github.com/renderghost/endlesss-studio-osc/blob/main/endless-studio-osc-1_0.jpeg)

## Features

**Version 1.0**
Everything mappable in *Endlesss Studio* can be mapped to *Endlesss Studio OSC*

- [x] BPM
- [x] Play / Pause
- [x] Looping
- [x] The Mixer
- [x] The Pad Buttons
- [x] The Effect Controls
- [x] Recording to the Sampler
- [x] Preset Selection

## Wishlist
- [ ] Switchable 2x Octave 🎹
- [ ] Pitchshifter
- [ ] Support for multiple device
- [ ] Feedback
- [ ] Metronome

## Requirements

To use the latest version of **Endlesss Studio OSC**, you will need:

- [Endlesss for Desktop](https://endlesss.fm/) running on OSX
- [TouchOSC Bridge](https://apps.apple.com/app/touchosc/id1569996730) running on OSX
- [TouchOSC](https://apps.apple.com/app/touchosc/id1569996730) running on an iPad Pro 12.9"

You will also need these files

- [Endlesss Studio OSC 1.0.tosc](https://github.com/renderghost/endlesss-studio-osc/blob/2cff50652fdaa44cae23730d1de5a2377d62f562/Endlesss%20Studio%20OSC%201.0.tosc)
- [Endlesss Studio OSC.midiprofile](https://github.com/renderghost/endlesss-studio-osc/blob/2cff50652fdaa44cae23730d1de5a2377d62f562/Endlesss%20Studio%20OSC.midiprofile)

## Installation

### Configure TouchOSC

Open **TouchOSC** on your iPad

1. Open the side menu by pressing the icon to the right of the tab bar
2. Press "Upload" (icon of a box with an upward-facing arrow) then "Import"
3. Choose `endlesss studio osc.tosc`
4. Press "Play" to use the patch

![touchosc.jpeg](https://github.com/renderghost/endlesss-studio-osc/blob/4bf43205acef9e9bb911625b1bfb674170f0e733/touchosc.jpeg)

### Configure Endlesss

Open **Endlesss** (standalone or VST) on your Mac

1. Open *Midi Mappings* (top-right)
2. **Import** `endlesss studio osc.midiprofile` into your list of *Midi Mappings* presets
3. Close *Midi Mappings* (top-right)

![endlesss.jpeg](https://github.com/renderghost/endlesss-studio-osc/blob/4bf43205acef9e9bb911625b1bfb674170f0e733/endlesss.jpeg)

## Further Reading

That's it!

- If you're struggling to get TouchOSC to speak to your iPad, read this guide by [Hexler](https://hexler.net/touchosc/manual/getting-started)
- Join the [Endlesss Community on Discord](https://discord.com/invite/hytvqRm)
