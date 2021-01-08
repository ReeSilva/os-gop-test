# Game of Pods test
This repository contains the solution for two lessons in the [Game of Pods](https://kodekloud.com/p/game-of-pods).

1. King`s Landing Voting App
2. The Wall: Iron gallery of Braavos

## How to run
For both lessons, I developed a single Kubernetes Yaml that applies everything that is needed, this way we can make it easy to manage by anyone, because is readable, avoid having to go from one file to another to find out everything.

### Lesson 1
The implementation of Lesson 1 comes from the file `k8stack-voting.yaml`.

This file creates the correct namespace and all resources needed. To do that:

`kubectl apply -f k8stack-voting.yaml`

### Lesson 2
This implementation comes from the file `k8stack-iron-gallery-braavos.yaml`.

As in lesson 1, this manifest creates all needed resources. To implement it:

`kubectl apply -f k8stack-iron-gallery-braavos.yaml`