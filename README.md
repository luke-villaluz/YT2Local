# YT2Local

A clean, minimal iOS app that downloads YouTube videos as MP3 files with proper metadata and saves them to Spotify's local files folder.

## Features

- Download YouTube videos as MP3 using ezmp3 API
- Clean video titles using OpenAI
- Fetch song metadata from Genius
- Embed metadata and album art into MP3 files
- Save to Spotify's local files folder
- Spotify-themed UI with editing capabilities

## Architecture

This app follows Clean Architecture principles with extreme separation of concerns:

- **Presentation Layer**: SwiftUI views and view models
- **Domain Layer**: Business logic, use cases, and protocols
- **Data Layer**: External services and repositories
- **Infrastructure Layer**: Configuration and utilities

## Setup

1. Clone the repository
2. Copy `.env.example` to `.env` and add your API keys
3. Open `YT2Local.xcodeproj` in Xcode
4. Build and run

## API Keys Required

- OpenAI API Key (for title cleaning)
- Genius API Key (for metadata)
- ezmp3 API Key (for YouTube downloads)

## Development

This project is built incrementally with clear checkpoints. Each component is isolated and testable.