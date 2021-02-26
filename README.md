## MERN Docker

![license](https://img.shields.io/badge/license-MIT-blue.svg)

> Simple C-R-U-D (Create, Read, Update, Delete) web app using MERN ([MongoDB](https://www.mongodb.com/), [Express (JS)](https://expressjs.com/), [React (JS)](https://reactjs.org/), [Node (JS)](https://reactjs.org/)) containerized via [Docker](https://www.docker.com/)

## To Do

- [ ] Create Express server app [Node Docker documentation](https://docs.docker.com/language/nodejs/build-images/)
	- [ ] Containerize server
		- [ ] Create api-server image from Dockerfile
- [ ] Create REACT client app
	- [ ] Containerize client
- [ ] Create MongoDB via docker
- [ ] Create Docker Compose file to orchestrate containerized spin up

  
## Prerequisites

- Node 12.18 or higher
- Docker / Docker Compose
	> [Docker Desktop](https://www.docker.com/products/docker-desktop) includes both and is recommended
- IDE
	> [VSCode](https://code.visualstudio.com/) is recommended

## Quick start

- [Download from Github](https://github.com/akeithly/mern-docker) or clone the repo: `git clone https://github.com/akeithly/mern-docker.git`

- Start the containers: `docker-compose up`

- Views are on: `localhost:3000`

## File Structure

Within the download you'll find the following directories and files:

```
mern-docker

├──  .vscode
│	├── extensions.json
│	├── launch.json
│	└── settings.json
├── .gitignore
├── LICENSE.md
├── README.md
├── client
└── server
```

## Reporting Issues:

- [Github Issues Page](https://github.com/akeithly/mern-docker/issues)

## License

- Licensed under MIT (https://github.com/akeithly/mern-docker/blob/master/LICENSE.md)
