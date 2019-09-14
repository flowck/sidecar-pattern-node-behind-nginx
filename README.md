# Sidecar Pattern: Proxy Server

This repository implements a Nodejs behind a proxy server using the [sidecar pattern](https://blog.davemdavis.net/2018/03/13/the-sidecar-pattern/).

## Goals

* Setup the deployment process of
  * Applicational container: Nodejs API running [JSON Placeholder](https://github.com/typicode)
  * Sidecar container running [Nginx](https://www.nginx.com/)
* Successfully deploy application on a Kubernetes cluster

## Non-Goals

* Implement a RESTfull API / webservice from scratch
