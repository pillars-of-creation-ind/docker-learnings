1. What is Docker ?

```
A platform for building, running and shipping applications in a consistent
manner.

Why Docker ?
- One or more files missing
- Software version mismatch
- Different configuration settings

With docker we can easily package up our application with everything it needs and run it anywhere or in any machine with docker
Consistently: build, run and ship applications
```

```bash
docker-compose up

docker-compose down --rmi all
```

2. Virtual Machines VS Containers

```
Virtual Machine: An abstraction of a machine (physical hardware)

Hypervisor: It is software we used to create and manage virtual machines
eg: VirtualBox, VMWare

Problem with VM
- Each VM needs a full blown OS
- Show to start
- Resource intensive

Containers: An isolated environment for running an application
- Allow running multiple apps in isolation
- Are lightweight
- Use OS of the host
- Start Quickly
- Need less hardware resources
```

3. Architecture of Docker
4. Installing Docker
5. Development Workflow
