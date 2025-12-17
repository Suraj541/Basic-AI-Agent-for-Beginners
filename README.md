# Basic-AI-Agent-for-Beginners
Basic AI agent for beginners. Shows how an agent takes input, processes it with simple logic or an LLM, and returns output. No frameworks, no hype. Built to teach core concepts clearly so you understand how AI agents actually work from scratch.

you can use this file for get agent workflow:

# Build Your First AI Agent.json 

This workflow is a basic AI chat agent built using n8n + LangChain. It listens for a chat message, passes the user input directly into an LLM chain, and returns the model’s response. This is the simplest possible agent loop.

How it works

Chat Trigger receives user input

Basic LLM Chain injects the input into a prompt

OpenRouter Chat Model runs llama-3.1-nemotron-70b-instruct

Edit Fields returns the raw response

Purpose

Teach beginners how an AI agent pipeline actually works

Show message flow, model binding, and execution order

No memory, no tools, no automation tricks
