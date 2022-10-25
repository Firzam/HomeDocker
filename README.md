
# Personnal Docker

A docker-compose project which regroup all tools use by me [@Grégory MOU KUI](https://github.com/Firzam).

It contains the following utilies:

- Administrative & Monitoring tools:
	- Portainer
	- Grafana

- Developpers tools:
	- GitLab
	- WebServer (Nginx)
	- DataBase (Postgresql)

- Utility tools:
	- Mail Server ()
	- DNS Server (PiHole)


## Installation

First of all we are going to install docker by running:
``sudo apt-get install docker-ce``

We check that docker has been throughly installed with `docker run hello-world`.
You can also use Docker Desktop if you prefer.


Before running the dockers' container run one of the script corresponding to your system:

- Linux script : `setup.sh`
- Windows script : `setup.batch`

Theses script create all directory needed for the containers volumes so we can persist all needed information like data, logs or config files.

Then run `docker-compose up`


## Documentation


