# Masaad | مْساعد

Secure conversational AI for Saudi eServices.
RAG over trusted service guides + task orchestration + privacy-preserving screen understanding.

![Badge](https://img.shields.io/badge/status-active-brightgreen)
![Badge](https://img.shields.io/badge/privacy-screen%20redaction-blue)
![Badge](https://img.shields.io/badge/arabic-ALLaM-purple)

## What it does
1. Understands the user’s intent (Problem solving / Step completion / Service explanation)
2. Guides step-by-step and detects missing requirements (slot filling)
3. Retrieves answers from a trusted knowledge base (RAG)
4. Optional voice experience (STT/TTS)
5. Can process user screenshots with sensitive data redacted (masked/hashed)

## Architecture
User Interface
Orchestrator Layer (Session Manager, Router, Task Classifier)
Core Intelligence (Dialogue Manager, ALLaM LLM + RAG + Slot Filling, Voice Engine)
Data Layer (Service Schemas, KB, Session & User State)
Integration Layer (User Profile, Absher / Backend APIs)
Security Layer (AuthN, AuthZ, Audit Logs, Encryption, Compliance, API Protection)

## Privacy by design
We never store raw screenshots.
Sensitive fields are detected and redacted before any processing.
Audit logs capture actions without exposing PII.

## Quickstart
```bash
# placeholder
# docker compose up
