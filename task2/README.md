# Go Hello World Application Deployment with Kubernetes

## Overview

This task focuses on deploying a simple Go "Hello World" application to a Kubernetes cluster. The application serves a JSON response with a "Hello, World!" message. The challenge involves identifying and fixing issues alone the way.

## Goals

- Successful deployed and fully working and running Go application

## Requirements

The solution needs to include:

- Go application that:
    - Returns a properly formatted JSON response with a "Hello, World!" message

- Dockerfile that:
    - Creates a functional go application image

- Kubernetes manifests that:
    - Runs the application correctly

- Helm chart that:
    - Runs the application correctly

## Dependencies

- Go
- Docker
- Local Kubernetes cluster
- kubectl command-line tool
- Helm package manager

## Architecture

The architecture consists of:

1. **Application Layer**: Go HTTP server application
2. **Container Layer**: Docker container packaging the application
3. **Deployment Layer**: Helm chart and Kubernetes resources for application deployment

## Evaluation Criteria

The solution will be evaluated based on:

1. Ability to identify and fix issues alone the way
2. Understanding of Go, containerization, and Kubernetes concepts
3. Ability to set up and use a local Kubernetes cluster
4. Quality and completeness of the solution
5. Clarity of documentation
