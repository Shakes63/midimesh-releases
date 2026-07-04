# MidiMesh

**One MIDI patchbay for the whole building.**

MidiMesh turns every computer, controller, console, and piece of show-control software on your network into a single virtual MIDI patchbay you wire together from one screen — like Dante for audio, but for MIDI. Send a stage keyboard to a sound module at front-of-house, let ProPresenter fire lighting cues on a console in another room, and trigger the whole rig from a Stream Deck — no cables run down the hallway, no engineer required.

**[Download for macOS &amp; Windows](https://github.com/Shakes63/midimesh-releases/releases/latest)** &nbsp;·&nbsp; **[Read the User Manual](https://shakes63.github.io/midimesh-releases/)**

## Why MidiMesh

- **Route MIDI anywhere on your network.** Connect any source to any destination across machines from one Routing Matrix — MidiMesh handles the networking for you, with sub-10&nbsp;ms delivery on a local network built for live shows. Merge several sources into one destination, or pair two endpoints into a two-way connection.
- **Bring in the gear you already have.** Bridge physical USB and DIN MIDI hardware onto the mesh with one click on macOS and Windows. Full MIDI 2.0 (high-resolution UMP) support, with automatic 7-bit clamping for classic MIDI 1.0 gear.
- **Talk to more than MIDI.** Built-in gateways for HTTP triggers &amp; webhooks, OSC, and RossTalk let MidiMesh drive QLab, X32/M32 mixers, Bitfocus Companion, Node-RED, PTZ cameras, video switchers, projectors, Stream Decks, and more. Outbound templates make each connection speak the receiver's exact vocabulary — like `/cue/5/start` or a camera preset URL.
- **Reshape messages on the fly.** Per-device translation tables remap MIDI as it's delivered — turn notes into CC, fix a stubborn footswitch, or latch a toggle — with nothing to reconfigure on the device itself.
- **Standards-based.** Speaks the MIDI Association's Network MIDI 2.0 (UDP) standard to interoperate with OS-native MIDI 2.0 and network-UMP devices.
- **Diagnosis in one glance.** A live activity log, per-link latency and health, plain-language warnings, a one-click test note, and an MSC/MMC cue-fire panel show you what's happening — and what's wrong — at a glance.
- **Run by volunteers.** Save and switch entire setups as named Scenes, back up and restore your whole configuration in a click, and secure the mesh with a single shared key. Native desktop apps for macOS and Windows.

## Who it's for

Churches and live-production teams running Stage and Front-of-House, ProPresenter into lighting, video, and show control across several machines — anywhere MIDI needs to travel the building reliably and be operated by volunteers, not network engineers.

## Get started

1. **[Download the latest installers](https://github.com/Shakes63/midimesh-releases/releases/latest)** for macOS and Windows.
2. Install the **Node** app on every machine with MIDI gear or software, and the **Controller** app wherever you'll run the show from.
3. Follow the **[User Manual](https://shakes63.github.io/midimesh-releases/)** to set up your first nodes, routes, and scenes.

## About this repo

This is the public home for MidiMesh's release binaries and `electron-updater` auto-update feeds (the app's source is private). Installers and per-platform feeds are attached to each release — grab the latest from the [Releases](https://github.com/Shakes63/midimesh-releases/releases) tab.
