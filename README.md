# Docker101
===============================


##### 1. what's docker
---------------

* Offical: Docker is an open platform for developping, shipping, and running(distributed) applications
* Container Creation/management software
* Performs OS-Level virtualization
* Simplifies deployment workflows
* Avoid the "it works on my machine" issue
* Local environments are equivalent to production environments
* Easy to use CI/CD technologies
* Using namespace `isolation` and cgroups `resorce contorl`
* Build once, Run anywhere

##### 2. Docker engine
---------------

Docker Engine is a client-server application with these major components:

* A server long-running daemon process(`dockerd` command)

* A Restful API talks with daemon process and instruct

* A command client line(CLI) client(`docker` command)

```bash
    CLI                                                         Server 
docker client   <---------->   Restful API  <----------->  docker daemon
```

![](images/docker-engine.png) 

What can I use Docker for？

1. Fast, consistent delivery of your applications
2. Responsive deployment and scaling
3. Running more workloads on the same hardware

##### 3. Architecture
---------------

Docker uses a client-server architecture.

![](architecture.png)

* 3.1 **The Docker Daemon**
* 3.2 **The Docker Client**
* 3.3 **The Docker registries**
* 3.4 **Docker Images**
* 3.5 **Docker Conatiners**


