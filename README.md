# Notes

This branch attempts to build and publish a custom Docker image to **Docker Hub** via Kaniko, using CircleCI machine executor.

See https://github.com/GoogleContainerTools/kaniko

## Important

I have injected the Docker credentials in a config file (JSON) under the `DOCKER_CONFIG_JSON` project env var.

For more information on how this worked, see https://github.com/GoogleContainerTools/kaniko#pushing-to-docker-hub
