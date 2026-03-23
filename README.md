# Cowhorse - AI Coding Orchestrator

An AI-powered coding assistant that runs inside Docker, uses Telegram as the frontend interface, and orchestrates CLI-based coding agents (such as gemini-cli) to handle programming tasks.

## Overview

Cowhorse is designed to be a self-hosted AI coding solution that:
- Runs entirely in Docker for easy deployment and isolation
- Accepts coding requests via Telegram bot interface
- Executes code generation/editing tasks using CLI-based AI agents like `gemini-cli`
- Provides a simple, accessible way to get AI coding assistance

## Architecture

- **Frontend**: Telegram Bot API
- **Backend**: Go orchestration layer
- **AI Engine**: CLI-based coding agents (gemini-cli/...)
- **Runtime**: Docker container

## License

Apache 2.0
