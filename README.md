# container-registry-playground
Trying out github's container registry and CI actions.

## Images
Individual images are automatically published to linked Github Container Registries:
- [service](https://github.com/users/rwakulszowa/packages/container/package/container-registry-playground-service)
- [client](https://github.com/users/rwakulszowa/packages/container/package/container-registry-playground-client)

## How to use
Refer to docker-compose files.

The idea is to provide an example of a simple web app with multiple components,
that can be developed without dependecies on anything but docker(compose).
The code can be edited and tested on a local NodeJS instance, without ever directly installing
NodeJS on the machine. The same applies to all other dependecies.

### Docker-compose files
Each docker-compose file contains a description on the very top.
Below is a short list of available files.

#### docker-compose.yml
The default file. Spins up the app for local development.

#### docker-compose.test.yml
Allows running end-to-end tests with a single command.
