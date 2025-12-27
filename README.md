# Whisper.rn — Real-Time Speech Transcription

A cross-platform mobile application built with **React Native** and **Expo** that performs **on-device speech-to-text transcription** using Whisper models.

Designed as a practical reference for real-time audio processing and native AI integration in mobile apps.

---

## Overview

This app demonstrates how to:
- Capture live microphone audio
- Process speech incrementally
- Run Whisper models locally
- Display transcription results in real time

It supports both **live transcription** and **audio file transcription**, with multiple Whisper model options.

---

## Key Capabilities

### Live Speech Recognition
- Continuous microphone listening
- Low-latency incremental transcription
- Automatic handling of pauses
- Final transcript aggregation

### Whisper Model Support
- Multiple model sizes available
- Automatic model download on first use
- Local storage and reuse
- Runtime model switching

### Audio File Processing
- Transcribe prerecorded audio
- Progress feedback during processing
- Sample audio included for testing

### User Interface
- Minimal, distraction-free layout
- Clear status indicators
- Real-time transcription output
- Simple transcript controls

---

## Setup & Installation

### Requirements
- Node.js 18+ or Bun
- Expo CLI
- iOS Simulator or physical iOS device
- Android emulator or physical Android device

### Install

```bash
git clone https://github.com/Vusoni/whisper-cpp-test.git
cd whisper-cpp-test

bun install
# or
npm install

npx expo prebuild
