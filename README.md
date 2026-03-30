# BPMN AI Modeler

A web-based BPMN modeling tool with:

- BPMN editor (bpmn-js)
- Visio (.vsdx) file inspector
- Integrated AI assistant (Langflow)

## Features

- Create and edit BPMN diagrams
- Upload and inspect Visio files
- Download BPMN XML
- AI chat assistant for document Q&A

## Tech Stack

- HTML / CSS / JavaScript
- bpmn-js
- JSZip
- Langflow embedded chat
- Nginx (for deployment)

## How to Run

### Option 1: Open locally
Open `public/index.html` in your browser.

### Option 2: Run with Docker
```bash
docker build -f docker/Dockerfile -t bpmn-ai .
docker run -p 8080:80 bpmn-ai
