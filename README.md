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
git clone https://github.com/Vusoni/WhisperAI-ReactNative.git
cd WhisperAI-ReactNative

npm install

npx expo prebuild
npm run ios  OR   npm run android

Using the App

First Launch
	1.	Open the app
	2.	Wait for the default model to finish loading
	3.	Approve microphone permissions

Live Transcription
	1.	Start the recording session
	2.	Speak naturally
	3.	View transcription as it updates
	4.	Stop to finalize the result

File Transcription
	1.	Trigger sample audio transcription
	2.	Wait for processing to complete
	3.	Review the generated transcript

Changing Models
	1.	Select a different model
	2.	Allow download if required
	3.	Model initializes automatically



  Limitations
	•	Background recording depends on OS policies
	•	Long sessions may impact performance
	•	WAV audio format is currently supported
	•	Memory usage scales with model size






