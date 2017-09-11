# Amaterasu Dev Machine Vagrant Setup

This repository contains the vagrentfile and provisioning script for creating an Amaterasu dev machine.

## prerequisites

Before you create a dev machine, make sure you have the Ametarasu source code, to do so, simply clone the Amaterasu git repo:

```
git clone https://github.com/shintoio/amaterasu.git
``` 

Change the directory to amaterasu-vagrant and start the machine:

```
cd amaterasu-demo-machine
vagrant up
```

Ssh to the vagrant machine:

```
vagrant ssh
```

## Getting started with Amatersu

If you are new to Amaterasu, the best way to start is to read out [introduction to Amaterasu](http://shinto.io/amaterasu/bigdata/devops/2016/09/22/introducing-materasu-continuously-deployed-big-data-pipelines.html) post.
