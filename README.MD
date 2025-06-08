# BeeKeeper

This project [HiveBox](https://devopsroadmap.io/projects/hivebox/) provided by the [Dynamic DevOps Roadmap](https://devopsroadmap.io/getting-started/) is lightweight tool to help beekeepers with their chores by tracking the environmental sensor data.

## Phases

### Phase 2
1. Create a function that prints the current app version.
2. Create a Dockerfile for the project.

```bash
#Build the image using the follwoing command
docker build -t beekeeper:0.0.1 .
#Run the container using the following command
docker run --rm beekeeper:0.0.1
```