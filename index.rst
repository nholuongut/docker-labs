# Welcome to Docker Labs

![My image](https://github.com/nholuongut/dockerlabs/blob/master/images/dockerlabs.jpeg)

Are you new to Docker? Want to build your career in Container Technology?

Then Welcome ! You are at the right place.

DockerLabs brings you tutorials that help you get hands-on experience using Docker & Kubernetes. Here you will find complete documentation of labs and tutorials that will help you, no matter if you are a beginner, SysAdmin, IT Pro or Developer. Yes, you read it right ! Its $0 learning platform. You don't need any infrastructure. Most of the tutorials runs on [Play with Docker Platform](https://labs.play-with-docker.com/) & [Play with Kubernetes Platform](https://play-with-k8s.com). This is a free browser based learning platform for you. Docker tools like Docker Engine, Docker Compose & Docker Machine are already installed. Hence, we have everything ready for you to get started with.

## Getting Started in 3 Simple Steps

- Join 200+ DockerLabs Contributors in 2 mins via [DockerLabs Slack Channel](https://tinyurl.com/y973wcq8)

- Fork, Contribute & Share via [DockerLabs GITHUB Repository](https://github.com/nholuongut/dockerlabs)

-  [![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/fold_left.svg?style=social&label=Follow%20%40nholuongut)](https://twitter.com/nholuongut)



# Categories

DockerLabs is a tutorials authored by members of the open community.
Below are the list of categories:

## Docker

- [Docker for Beginners](https://github.com/nholuongut/dockerlabs/tree/master/beginners/README.md)

- [Docker for Intermediate](https://github.com/nholuongut/dockerlabs/tree/master/intermediate/README.md)

- [Docker for Advanced](https://github.com/nholuongut/dockerlabs/tree/master/advanced/README.md)

- [Docker for CIOs/CEOs](https://github.com/nholuongut/dockerlabs/tree/master/docker/leadership/README.md)

- [Docker Cheatsheet](https://github.com/nholuongut/dockerlabs/tree/master/docker/cheatsheet/README.md)

- [Docker Interview Questions]()


## Kubernetes

- [Kubernetes for Beginners](https://github.com/nholuongut/dockerlabs/tree/master/kubernetes/README.md)

- [Kubernetes for Intermediate](https://github.com/nholuongut/dockerlabs/tree/master/kubernetes/README.md)

- [Kubernetes for Advanced](https://github.com/nholuongut/dockerlabs/tree/master/kubernetes/README.md)

- [Kubernetes for CIOs/CEOs](https://github.com/nholuongut/dockerlabs/tree/master/kubernetes/leadership/README.md)

- [Kubernetes Cheatsheets](https://github.com/wikitops/dockerlabs/tree/master/kubernetes/cheatsheets)

- [Kubernetes Interview Questions]()

# A Quick Reference

## Getting Started with Docker

Interestingly, you don't need to do any investment. Throughout the tutorial, you will be using Play with Docker (PWD in short) Playground. Cool....Isn't it?

PWD is a Docker playground which allows users to run Docker commands in a matter of seconds. It gives the experience of having a free Alpine Linux Virtual Machine in browser, where you can build and run Docker containers and even create clusters in Docker Swarm Mode. Under the hood Docker-in-Docker (DinD) is used to give the effect of multiple VMs/PCs.

To get started with Docker, follow the below steps:

- Create Dockerhub Account

- Open [Play with Docker Platform](https://labs.play-with-docker.com/)

- Click on "Start"

- This will open up an easy to understand PWD(Play with Docker) tool which displays instances on the left hand side while terminal at the right hand side

- Click on "Create Instance" to create your first Linux instance

## Getting Started with Docker Swarm

To get started with Docker Swarm, you can use "Play with Docker", aka PWD.
It's free of cost and open for all.
You get maximum of 5 instances of Linux system to play around with Docker.

- Open [Play with Docker labs](https://labs.play-with-docker.com) on your browser

- Click on Icon near to Instance to choose 3 Managers & 2 Worker Nodes

![My image](https://github.com/nholuongut/dockerlabs/blob/master/images/pwd_1.png)

- Wait for few seconds to bring up 5-Node Swarm Cluster

We recommend you start with one of our Beginners Guides, and then move to intermediate and expert level tutorials that cover most of the features of Docker. For a comprehensive approach to understanding Docker, I have categorized it as shown below:

# A Bonus... Docker Swarm Visualizer

Swarm Visualizer is a fancy tool which visualized the Swarm Cluster setup. It displays containers running on each node in the form of visuals. If you are conducting Docker workshop, it's a perfect way to show your audience how the containers are placed under each node. Go..try it out..

## Clone the Repository

```docker
git clone https://github.com/dockersamples/docker-swarm-visualizer
```

```docker
cd docker-swarm-visualizer
docker-compose up -d
```

![My image](https://github.com/nholuongut/dockerlabs/blob/master/images/visualizer.png)

To run in a docker swarm:

```docker
$ docker service create \
  --name=viz \
  --publish=8080:8080/tcp \
  --constraint=node.role==manager \
  --mount=type=bind,src=/var/run/docker.sock,dst=/var/run/docker.sock \
  dockersamples/visualizer
```

## How to Contribute

Thank you so much for showing your interest in contributing to [Dockerlabs](https://github.com/nholuongut/dockerlabs) tutorials.

[Guide to submitting your own tutorial](https://github.com/nholuongut/dockerlabs/tree/master/CONTRIBUTING.md)<br>
[Template for writing Tutorial Page](https://github.com/nholuongut/dockerlabs/tree/master/template/EXAMPLE.md)

## Docker-Ready Stack for You

In case you're looking out to conduct workshop or demo, you can refer these below links to bring up Application Stack in no time.

- [Docker + WordPress + Docker Swarm](https://github.com/nholuongut/dockerlabs/tree/master/solution/wordpress/README.md)

- [Docker + Elasticsearch + Logstash + Kibana + Docker Swarm](https://github.com/nholuongut/dockerlabs/tree/master/play-with-docker/ELK/README.md)

- [Docker, Prometheus Stack + Docker Swarm](https://github.com/nholuongut/dockerlabs/tree/master/play-with-docker/docker-prometheus-swarm/README.md)

- [Docker + Apache Jmeter + Docker Swarm Mode](https://github.com/nholuongut/dockerlabs/tree/master/play-with-docker/jmeter-docker/README.md)

- [Docker + Voting App Example](https://github.com/nholuongut/dockerlabs/tree/master/play-with-docker/example-voting-app/README.md)

- [Docker + Photon OS](https://github.com/nholuongut/dockerlabs/tree/master/play-with-docker/vmware/powercli/README.md)

- [Docker + MacVLAN](https://github.com/nholuongut/dockerlabs/tree/master/play-with-docker/macvlan/README.md)

- [Docker, Docker Compose & IPv6](https://github.com/nholuongut/dockerlabs/tree/master/play-with-docker/ipv6/README.md)

- [Docker + GitLab](https://github.com/nholuongut/dockerlabs/tree/master/play-with-docker/gitlab/README.md)

- [Docker + Nginx ](https://github.com/nholuongut/dockerlabs/tree/master/play-with-docker/nginx/README.md)

- [Docker + Django + PostgreSQL](https://github.com/nholuongut/dockerlabs/blob/master/solution/django-postgres/readme.md)

- [Docker + Gomodule](https://github.com/nholuongut/dockerlabs/blob/master/beginners/httpserver_go_module_and_docker.md)
## License

[MIT](https://github.com/nholuongut/dockerlabs/blob/master/LICENSE.md)

   [Proceed to Beginners Track >>](https://github.com/nholuongut/dockerlabs/blob/master/beginners/README.md)
