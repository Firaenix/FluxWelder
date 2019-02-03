# FluxWelder

A visual companion tool to Weave Flux - Run Fluxctl commands from a web interface

## Aim:

### To provide a web interface for orchestrating releases across multiple Kubernetes clusters using Weave Flux

### Should allow work load promotion across environments.

Test -> Stage -> Live

## To Do:

- Create Dockerfile
- Write Rust Backend
- Call Fluxctl from Rust backend
- Authenticate against Kubernetes API Server
- Store kubeconfig
- Write React Frontend

## Commands:

- Fluxctl sync
- Fluxctl automate
- Fluxctl release -c "{Controller}:version"
