[![CircleCI](https://circleci.com/gh/giantswarm/hivemq-operator-app.svg?style=shield)](https://circleci.com/gh/giantswarm/hivemq-operator-app)

# hivemq-operator chart

Giant Swarm offers the hivemq-operator which can be installed in workload clusters.
Here we define the hivemq-operator chart with its templates and default configuration.

The HiveMQ Kubernetes Operator is an application-specific controller that allows DevOps to orchestrate and manage the lifecycle of a HiveMQ cluster deployment within Kubernetes. The HiveMQ Kubernetes Operator runs as a custom controller on Kubernetes and communicates with the Kubernetes API Server (kube-api server) to convert high-level descriptions into normal Kubernetes resources that maintain the desired application state:

* Automate orchestration of your entire HiveMQ deployment (platform agnostic) on Kubernetes
* Monitor, maintain, recover, and upgrade your HiveMQ application with ease
* Automatically deploy and operate HiveMQ on your Kubernetes cluster with custom or enterprise extensions

The HiveMQ Kubernetes Operator can run and maintain multiple HiveMQ clusters.

## Installing

There are 3 ways to install this app onto a workload cluster.

1. [Using our web interface](https://docs.giantswarm.io/ui-api/web/app-platform/#installing-an-app)
2. [Using our API](https://docs.giantswarm.io/api/#operation/createClusterAppV5)
3. Directly creating the [App custom resource](https://docs.giantswarm.io/ui-api/management-api/crd/apps.application.giantswarm.io/) on the management cluster.

## Configuring

Configuration values are documented in [`helm/hivemq-operator/README.md`](https://github.com/giantswarm/hivemq-operator-app/blob/master/helm/hivemq-operator/README.md).

See our [full reference page on how to configure applications](https://docs.giantswarm.io/app-platform/app-configuration/) for more details.

## Compatibility

This app has been tested to work with the following workload cluster release versions:

* Kubernetes >= 1.19.x

## Credit

* https://github.com/hivemq/helm-charts/
