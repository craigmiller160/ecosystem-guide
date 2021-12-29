# Infrastructure

I've got a robust application infrastructure setup. This includes a locally running Kubernetes cluster, Sonatype Nexus as a repository, and a full build tool that validates, builds, and deploys projects. Here is a summary of that infrastructure.

## Main Setup Repo

[LocalKubernetesDeployment](https://github.com/craigmiller160/LocalKubernetesDeployment)

This repository contains all the information needed to setup the locally running Kubernetes environment from scratch. It also contains the kubernetes configurations for shared resources like databases and the Sonatype Nexus repository. Also networking instructions, TLS certs, all of that can be found here.

## Build Tool

[craig-build](https://github.com/craigmiller160/craig-build)

This repository contains `craig-build`, which is the full build/validation/deployment tool that I have written. This automates all the steps I want to apply when producing a "real" project for use in this ecosystem.
