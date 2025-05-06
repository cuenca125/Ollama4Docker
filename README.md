# Ollama4Docker
## Basic ollama application with a web interface (openweb-ui), ready for deploying it on Docker.

The compose file or YAML deploys a working ollama service and a web interface (openweb-ui) for this service. You'll be prompted to create an account and then you can download your preferred LLM model and start using it trough the openweb-ui interface.
**(none of your information goes on the internet, even knowing that i suggest using fake email and username that you'll remember)**

This YAML file can be run on docker with the following command: 
```
docker compose -f Ollama4Docker.yaml up
```
> [!IMPORTANT]
> **(Make sure you are on the same directory as the Ollama4Docker.yaml file before you run the command)**.  

<!-- With luv cuenca -->
