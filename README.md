# Local Llama 3 UI with RAG functionality
Chat UI with local offline RAG functionality for using Llama3 Model.

## Architecture
![Alt text](architecture.png?raw=true "Architecture")

## OpenWebUI
![Alt text](demo-6793d95448aa180bca8dafbd21aa91b5.gif?raw=true "Open WebUI Demo")

## Prerequisites
- Install Ollama - https://ollama.com/
- Install Docker - https://docs.docker.com/engine/install/

## Download Llama 3 model 
In your terminal:

  `ollama pull llama3:latest`

## Pull and run open-webui docker image
In your terminal:

  `docker run -d -p 3000:8080 --add-host=host.docker.internal:host-gateway -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:main`

## Open the open-webui application

  http://localhost:3000/


  
