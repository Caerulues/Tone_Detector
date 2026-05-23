# Tone Detector

[简体中文](./README_zh_CN.md)

A modern real-time pitch detector and tuner built with SwiftUI and AudioKit.

## Features

- Real-time pitch detection
- Scientific pitch notation
- Smooth animated tuner needle
- Dynamic note strip UI
- AudioKit-powered DSP
- Low-latency microphone input
- SwiftUI interface
- iOS support
- macOS support

## Screenshots

<img width="301.5" height="596.25" alt="image" src="https://github.com/user-attachments/assets/eb4fbdd6-b254-4f74-bcc3-196f45fb3fdc" />

## Tech Stack

- SwiftUI
- AudioKit
- AVAudioEngine
- SoundpipeAudioKit

## Architecture

```text
Microphone
↓
AVAudioEngine
↓
AudioKit PitchTap
↓
Pitch Analysis
↓
Pitch Mapping
↓
SwiftUI Rendering
````

### Requirements

* iOS 18+
