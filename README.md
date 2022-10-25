
# Personnal Docker

A docker-compose project which regroup all tools use by me [@Grégory MOU KUI](https://github.com/Firzam).

It contains the following utilies:

- Administrative & Monitoring tools:
	- Portainer
	- Grafana (yet to be implemented)

- Developpers tools:
	- GitLab (yet to be implemented)
	- Rever Proxy (Nginx)
	- WebServer (Apache/PHP)
	- DataBase (Postgresql)

- Utility tools:
	- Mail Server (yet to be implemented)


## Installation

First of all we are going to install docker by running:
``sudo apt-get install docker-ce``

We check that docker has been throughly installed with `docker run hello-world`.
You can also use Docker Desktop if you prefer.

(Those script are not up yet need to be done as Linux does not auto create directory if needed)
Before running the dockers' container run one of the script corresponding to your system:

- Linux script : `setup.sh`
- Windows script : `setup.batch`

Theses script create all directory needed for the containers volumes so we can persist all needed information like data, logs or config files.

Then run `docker-compose up`


## Documentation


