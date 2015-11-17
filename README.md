docker-paas
==============

## Prerequisite

Before installing the project, make sure that you have the latest version of :

- Docker Engine
- Docker Compose 
- Docker Machine

## Installation

Clone the repository:

```bash
$ git clone https://github.com/CtrlWebInc/docker-paas.git
```

Then, run:

```bash
$ docker-compose up -d 
```

Woah! That's it! You got a full up and running PaaS server!
All you need to do is for your other docker containers to "expose" port 80 
instead of using "port", and to add an environment variable VIRTUALHOST set
to the virtual host domain name you want to access your app.  Voila!
