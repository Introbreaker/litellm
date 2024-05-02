# LiteLLM - DOCKER Deployment

For those who need a load balancer for LLM's using Ollama/Openai/Groq etc.

Included is a docker-compose file that spins up a PostresDB and LiteLLM. The config is done by changing the config.yml.

## Getting started

To get up and running, create a **.env** file example below:

```env
OLLAMA_API_BASE=https://localhost:11434
OLLAMA_API_KEY=OLLAMA
```

Enjoy!
