# dowegettacos.today-docker

Repository to hold Vagrant and Docker code for the dowegettacos.today project

## Getting Started on Development

<!-- These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system. -->

This project provides you with a Vagrantfile to use Vagrant + Ubuntu 16.04.

* Install Vagrant and VirtualBox
  * Install Vagrant's docker-compose plugin: `vagrant plugin install vagrant-docker-compose`
  * Install Vagrant's guest additions update: `vagrant plugin install vagrant-vbguest`
* Clone this repo (dowegettacos.today-docker)
  * `cd` into dowegettacos.today-docker
* Clone dowegettacos.today inside the dowegettacos.today-docker/app folder.
* Run `vagrant up`
* Run `vagrant ssh` to work in the Vagrant environment


When you're done:
* Run `vagrant halt`

### Prerequisites

<!-- What things you need to install the software and how to install them

```
Give examples
``` -->
#### Development

Vagrant + VirtualBox
git

#### Production

Docker + Docker Compose

## Deployment

* Install docker and docker-compose
* Clone this repo to the folder of your choosing
* Run `docker-compose up -d`
