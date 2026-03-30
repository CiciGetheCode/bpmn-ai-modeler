# BPMN AI Modeler

A browser-based BPMN editor that supports Visio (.vsdx) inspection and AI-assisted document Q&A for workflow modeling.

## Features

- Create and edit BPMN diagrams
- Upload and inspect Visio (.vsdx) files
- Download BPMN XML
- Use an embedded AI assistant for document Q&A

## Tech Stack

- HTML / CSS / JavaScript
- bpmn-js
- JSZip
- Langflow embedded chat
- Nginx / Docker

## Status

In progress — functional prototype for BPMN editing, Visio inspection, and AI-assisted workflow support.

## How to Run

### Option 1: Open locally
Open `public/index.html` in your browser.

### Option 2: Run with Docker
```bash
docker build -f docker/Dockerfile -t bpmn-ai .
docker run -p 8080:80 bpmn-ai
