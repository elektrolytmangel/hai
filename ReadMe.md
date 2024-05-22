# Get up and running with open-webui (a gpt-application)
This repo contains mainly a docker-compose configuration to start open-webui with ollama and run it locally on a machine. 
It generates automatically a ssl-certificate (with caddy) and exposes port 443 where the application can be accessed over browser. 
Watchtower check each day for updates, and would update the docker-images automatically.

## Configuration
Add your openai-api-key to the .env file to use openai models out of the box.

## Start
```docker compose up -d```

## Additional info
Open-webui has more options i.e. usage for gpu and additional stuff. this can added here as well if needed.