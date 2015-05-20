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

### Todo's

 - Create a docker img
 - Update and commit 
 - Add Code Comments
