# Tripwire

Catching AI data leaks with decoy documents.

## The problem
Companies connect internal files to AI chatbots. If someone tricks the bot, private data can leak and nobody notices.

## Our idea
We hide fake documents (decoys) inside the chatbot's knowledge. Real staff never need them. If the bot ever shows or uses one, Tripwire raises an alert and blocks that session.

## Planned stack
Node.js, Express, an LLM API, a simple alert dashboard.

## Status
Idea stage. Built for CyberForge 2026 (Mitigata x HackCulture).
