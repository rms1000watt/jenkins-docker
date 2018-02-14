# Jenkins Docker

## Introduction

Jenkins Docker image with Docker installed

## Contents

- [Build](#build)
- [Push](#push)

## Build

```bash
docker build --force-rm --no-cache --compress -t rms1000watt/jenkins-docker:latest .
```

## Push

```bash
docker push rms1000watt/jenkins-docker:latest
```