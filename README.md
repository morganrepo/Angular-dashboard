# My Dashboard

This is Dashboard is a web-based UI for Admin, allowing users to see information and more for the Admin applications, components, and configurations running either locally or in a Kubernetes cluster.

## Features

Admin Dashboard provides information about Admin applications, components, configurations, and control plane services. Users can view metadata, manifests and deployment files, actors, logs, and more on both Kubernetes and self-hosted platforms. For more information, check out the [changelog].

### Installation

Admin Dashboard comes pre-packaged with the Admin CLI. To learn more about the dashboard command, use the CLI command `Admin dashboard -h`.

#### Kubernetes
Run `Admin dashboard -k`, or if you installed Admin in a non-default namespace, `Admin dashboard -k -n <your-namespace>`.

#### Standalone
Run `Admin dashboard`, and navigate to http://localhost:8080.
