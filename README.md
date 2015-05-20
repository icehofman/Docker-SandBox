# Docker windows environment

### Installation

You need Git installed to use ssh:
```sh
C:\Program Files (x86)\Git\cmd\start-ssh-agent.cmd
```

Set path where the executables will be stored and set the environment path on the System:
```sh
$ mkdir c:\docker && cd c:\docker
$ curl -L -k https://get.docker.com/builds/Windows/x86_64/docker-latest.exe > /docker/docker.exe
$ curl -L -k https://github.com/docker/machine/releases/download/v0.2.0/docker-machine_windows-amd64.exe > /docker/docker-machine.exe
```

Check version:
```sh
$ docker-machine -v
```

Show all available machines:
```sh
$ docker-machine ls
```

Create a machine:
```sh
$ docker-machine create --driver virtualbox dev
```

Set the active machine:
```sh
$ docker-machine active dev
```

Remove machine:
```sh
$ docker-machine rm dev
```

### Todo's

 - Create a docker img
 - Update and commit 
 - Add Code Comments
