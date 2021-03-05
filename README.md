# Personal Docker Compose Library

Applications I use, ready to launch using [Docker Compose](https://docs.docker.com/compose/).

## TL;DR

```bash
git clone git@github.com:barrelmaker97/compositions.git
docker-compose -f <directory>/<compose-file> up -d
```

## Before you begin

### Prerequisites
- Docker
- Docker Compose

### Install Docker

To install Docker, refer to the [Docker install guide](https://docs.docker.com/get-docker/).

### Install Docker Compose

Docker Compose is a tool for defining and running multi-container Docker applications. A compose file is used to configure your application’s services.

To install Docker Compose, refer to the [Docker Compose install guide](https://docs.docker.com/compose/install/).

### Clone Repo

The following command allows you to download and use all the compose files from this repository:

```bash
git clone git@github.com:barrelmaker97/compositions.git
```

### Using Docker Compose

Once you have installed Docker Compose, you can deploy Docker containers/services.

Please refer to the [Command Line Reference](https://docs.docker.com/compose/reference/) for detailed instructions on how to use the Docker Compose client to manage your container deployments.

Useful Docker Compose Commands:
* Install a compose file, detached from the terminal: `docker-compose -f <compose-file> up -d`
* Delete a deployment: `docker-compose -f <compose-file> down`
* Pull latest images: `docker-compose -f <compose-file> pull`

# License

Copyright (c) 2021 Nolan Cooper

This composition collection is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This composition collection is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this composition collection.  If not, see <https://www.gnu.org/licenses/>.
