# eco_configs

## Usage

To populate the Configs and Mods directories, run the following:

```bash
ECO_TAG=0.9.0.0-beta-staging-1774 make run
```

ECO_TAG is the tag of the docker image here: 

https://hub.docker.com/r/strangeloopgames/eco-game-server/tags

You can now utilize the `Mods` and `Configs` folders as volumes in the Docker deployment.
This is useful for deploying your own configurations and customizations.
