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


{
Step-by-Step: Setting Up OpenRouter Credentials in n8n

    1.Create an OpenRouter Account
        Go to https://openrouter.ai/ and sign up for a free account if you don’t have one.

    2.Get Your API Key
        After logging in, visit your API keys page: https://openrouter.ai/keys.
        Click on “Create new secret key.” You can give your key a name to remember what it’s for.
        Copy the API key that is generated.

    3.Add the API Key to n8n
        In n8n, go to the Credentials section.
        Click “New Credential” and search for “OpenRouter.”
        Paste your API key into the “API Key” field.
        Save the credential.

    4.Use the Credential in Your Workflow
        When you add an OpenRouter node (like “Chat OpenRouter”) to your workflow, select the credential you just created.

}
