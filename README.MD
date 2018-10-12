# Minikube VM

This repo contains a Vagrant script that boots a VM with Kubectrl and Minikube installed so that you can experiment with Kubernetes on a dev PC.

## Source

[https://kubernetes.io/docs/setup/minikube/](https://kubernetes.io/docs/setup/minikube/)

## Setup

Make sure you have VirtualBox and Vagrant installed.

## Starting the VM

    vagrant up

##  Shell into the VM

    vagrant ssh

## To start Minikube

    sudo minikube start --vm-driver=none