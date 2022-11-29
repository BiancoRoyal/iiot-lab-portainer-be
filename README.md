# iiot-lab-portainer-be



## Docker Install

[Docker Docs](https://docs.docker.com/engine/install/debian/)


## Portainer EE

    docker run -d -p 8000:8000 -p 9443:9443 --name=portainer --restart=always \
    -v /var/run/docker.sock:/var/run/docker.sock \
    -v portainer_data:/data \
    portainer/portainer-ee:latest

## WAGO Docker Package (IPK)

[GitHub Repo](https://github.com/WAGO/docker-ipk)

The time has to be set by the clock inside the WBM of the controller.

## Controller Portainer Edge Agent

Use the edge agent command to install and run the edge agent on the controller.
