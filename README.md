# tangserver

This repo is meant to be part of an overall lab deployment for RHEL systems. It contains the ansible plays and roles to deploy a tang server as a container on a server running podman. 
This can be a new server instance created from Satellite hostgroup or an existing host. 

### Use Case
You are building out a Red Hat Standard infrastructure. You what to implement Network Bound Disk Encryption as part of the environment. Deploy multiple servers that act as container hosts. Add a tang server container running on each host. Add the tang urls to the global parameters of the satellite server for use in encrytped volume deployments.

