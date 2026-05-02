# Architecture Overview

## Purpose

Slectnplay is a Windows desktop Text-to-Speech application designed to convert selected text into audio locally on the user's device. It supports reading-heavy workflows such as reviewing code, logs, documentation, technical text, and long-form content.

## High-Level Flow

At a high level, the user selects text, releases the mouse, and Slectnplay prepares the selected content for local audio playback. The application is designed to make text easier to consume without requiring the user to remain visually focused on the screen.

## Main Components

Slectnplay can be described through a small set of product-level components:

- A desktop interaction layer for selecting text and controlling playback.
- A text preparation layer for making selected content suitable for spoken output.
- A local voice layer that converts prepared text into audio.
- A playback layer that outputs the generated speech on the user's device.

## Offline Processing

Slectnplay uses local voice assets for Text-to-Speech playback. Text processing and audio generation are performed on the user's device without cloud processing.

## Privacy Boundary

Selected text remains local to the user's device. Slectnplay does not collect, transmit, store, sell, or share user data, and it does not use analytics, advertising, or third-party data collection.

## Repository Scope

This repository is for public portfolio and product documentation only. It does not include proprietary source code, local voice models, packaged binaries, installers, signing material, private configuration, or internal implementation logic.
