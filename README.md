# homelab-k8s

[![Lint](https://github.com/loganmarchione/homelab-k8s/actions/workflows/lint.yml/badge.svg)](https://github.com/loganmarchione/homelab-k8s/actions/workflows/lint.yml)

A K3s cluster defined as code

## Stack

### Core

The core components of the cluster

<table>
    <tr>
        <th>Logo</th>
        <th>Name</th>
        <th>Description</th>
    </tr>
    <tr>
        <td><img vertical-align=baseline width="32" src="https://raw.githubusercontent.com/loganmarchione/svg-assets/main/assets/k3s.svg"></td>
        <td><a href="https://k3s.io/">K3s</a> (<a href="https://github.com/k3s-io/k3s">source</a>)</td>
        <td>Lightweight Kubernetes</td>
    </tr>
    <tr>
        <td><img vertical-align=baseline width="32" src="https://raw.githubusercontent.com/loganmarchione/svg-assets/main/assets/traefik-gopher.svg"></td>
        <td><a href="https://traefik.io/">Traefik</a> (<a href="https://github.com/traefik/traefik">source</a>)</td>
        <td>Kubernetes Ingress Controller</td>
    </tr>
    <tr>
        <td><img vertical-align=baseline width="32" src="https://raw.githubusercontent.com/loganmarchione/svg-assets/main/assets/helm.svg"></td>
        <td><a href="https://helm.sh/">Helm</a> (<a href="https://github.com/helm/helm">source</a>)</td>
        <td>The Kubernetes Package Manager</td>
    </tr>
    <tr>
        <td><img vertical-align=baseline width="32" src="https://raw.githubusercontent.com/loganmarchione/svg-assets/main/assets/fluxcd.svg"></td>
        <td><a href="https://fluxcd.io/">Flux CD</a> (<a href="https://github.com/fluxcd/flux2">source</a>)</td>
        <td>Continuous delivery solution for Kubernetes</td>
    </tr>
</table>

### `cluster/infrastructure`

The infrastructure that everything else depends on

<table>
    <tr>
        <th>Logo</th>
        <th>Name</th>
        <th>Description</th>
    </tr>
    <tr>
        <td><img vertical-align=baseline width="32" src="https://raw.githubusercontent.com/loganmarchione/svg-assets/main/assets/rancher.svg"></td>
        <td><a href="https://github.com/rancher/local-path-provisioner/">Local Path Provisioner</a></td>
        <td>Local storage based on <code>hostPath</code> and <code>local</code> storage providers</td>
    </tr>
    <tr>
        <td><img vertical-align=baseline width="32" src="https://raw.githubusercontent.com/loganmarchione/svg-assets/main/assets/certmanager.svg"></td>
        <td><a href="https://cert-manager.io/">cert-manager</a> (<a href="https://github.com/cert-manager/cert-manager">source</a>)</td>
        <td>X.509 certificate management for Kubernetes</td>
    </tr>
    <tr>
        <td><img vertical-align=baseline width="32" src="https://raw.githubusercontent.com/loganmarchione/svg-assets/main/assets/kubernetes.svg"></td>
        <td><a href="https://github.com/stakater/Reloader/">reloader</a></td>
        <td>A Kubernetes controller that automatically triggers rollouts of workloads whenever referenced Secrets or ConfigMaps are updated</td>
    </tr>
    <tr>
        <td><img vertical-align=baseline width="32" src="https://raw.githubusercontent.com/loganmarchione/svg-assets/main/assets/postgresql.svg"></td>
        <td><a href="https://cloudnative-pg.io/">CloudNativePG</a> (<a href="https://github.com/cloudnative-pg/cloudnative-pg">source</a>)</td>
        <td>Seamlessly manage PostgreSQL databases within Kubernetes environments</td>
    </tr>
</table>

### `cluster/apps`

The applications that run in my homelab (listed in alphabetical order)

<table>
    <tr>
        <th>Logo</th>
        <th>Name</th>
        <th>Description</th>
    </tr>
    <tr>
        <td><img vertical-align=baseline width="32" src="https://raw.githubusercontent.com/loganmarchione/svg-assets/main/assets/visualstudiocode.svg"></td>
        <td><a href="https://hub.docker.com/r/linuxserver/code-server">Code Server</a> (<a href="https://github.com/linuxserver/docker-code-server">source</a>)</td>
        <td>A Dockerized version of <a href="https://github.com/coder/code-server">code-server</a></td>
    </tr>
    <tr>
         <td><img vertical-align=baseline width="32" src="https://raw.githubusercontent.com/loganmarchione/svg-assets/main/assets/cyberchef.svg"></td>
        <td><a href="https://github.com/gchq/CyberChef">CyberChef</a></td>
        <td>GCHQ's Cyber Swiss Army Knife</td>
    </tr>
    <tr>
        <td><img vertical-align=baseline width="32" src="https://raw.githubusercontent.com/loganmarchione/svg-assets/main/assets/diagramsdotnet.svg"></td>
        <td><a href="https://hub.docker.com/r/jgraph/drawio">Diagrams.net (aka Draw.io)</a> (<a href="https://github.com/jgraph/drawio">source</a>)</td>
        <td>Diagram creation</td>
    </tr>
    <tr>
        <td><img vertical-align=baseline width="32" src="https://raw.githubusercontent.com/loganmarchione/svg-assets/main/assets/homebox.svg"></td>
        <td><a href="https://github.com/sysadminsmedia/homebox">HomeBox</a></td>
        <td>A continuation of HomeBox the inventory and organization system built for the Home User</td>
    </tr>
    <tr>
        <td><img vertical-align=baseline width="32" src="https://raw.githubusercontent.com/loganmarchione/svg-assets/main/assets/ittools.svg"></td>
        <td><a href="https://hub.docker.com/r/corentinth/it-tools">IT-Tools</a> (<a href="https://github.com/CorentinTh/it-tools">source</a>)</td>
        <td>Collection of handy online tools for developers</td>
    </tr>
    <tr>
        <td><img vertical-align=baseline width="32" src="https://raw.githubusercontent.com/loganmarchione/svg-assets/main/assets/kubernetes.svg"></td>
        <td><a href="https://github.com/kubernetes/dashboard">Kubernetes dashboard</a></td>
        <td>General-purpose web UI for Kubernetes clusters</td>
    </tr>
    <tr>
        <td><img vertical-align=baseline width="32" src="https://raw.githubusercontent.com/loganmarchione/svg-assets/main/assets/pairdrop.svg"></td>
        <td><a href="https://hub.docker.com/r/linuxserver/pairdrop">PairDrop</a> (<a href="https://github.com/linuxserver/docker-pairdrop">source</a>)</td>
        <td>Transfer files cross-platform (AirDrop alternative)</td>
    </tr>
    <tr>
        <td><img vertical-align=baseline width="32" src="https://raw.githubusercontent.com/loganmarchione/svg-assets/main/assets/postgresql.svg"></td>
        <td><a href="https://hub.docker.com/r/dpage/pgadmin4">pgAdmin 4</a> (<a href="https://github.com/pgadmin-org/pgadmin4">source</a>)</td>
        <td>Web-based management tool for Postgres</td>
    </tr>
    <tr>
        <td><img vertical-align=baseline width="32" src="https://raw.githubusercontent.com/loganmarchione/svg-assets/main/assets/portainer.svg"></td>
        <td><a href="https://www.portainer.io/">Portainer</a> (<a href="https://github.com/portainer/portainer">source</a>)</td>
        <td>Web-based management for Kubernetes</td>
    </tr>
    <tr>
        <td><img vertical-align=baseline width="32" src="https://raw.githubusercontent.com/loganmarchione/svg-assets/main/assets/docker.svg"></td>
        <td><a href="https://hub.docker.com/_/registry">Registry</a> (<a href="https://github.com/distribution/distribution">source</a>)</td>
        <td>Docker image registry</td>
    </tr>
    <tr>
        <td><img vertical-align=baseline width="32" src="https://raw.githubusercontent.com/loganmarchione/svg-assets/main/assets/stirlingpdf.svg"></td>
        <td><a href="https://hub;docker.com/r/frooodle/s-pdf">StirlingPDF</a> (<a href="https://github.com/Stirling-Tools/Stirling-PDF">source</a>)</td>
        <td>Web-based PDF manipulation tool</td>
    </tr>
    <tr>
        <td><img vertical-align=baseline width="32" src="https://raw.githubusercontent.com/loganmarchione/svg-assets/main/assets/stringis.svg"></td>
        <td><a href="https://hub.docker.com/r/daveperrett/string-is">string.is</a> (<a href="https://github.com/recurser/string-is">source</a>)</td>
        <td>An open-source, privacy-friendly online string toolkit for developers</td>
    </tr>
    <tr>
        <td><img vertical-align=baseline width="32" src="https://raw.githubusercontent.com/loganmarchione/svg-assets/main/assets/traefik-gopher.svg"></td>
        <td><a href="https://doc.traefik.io/traefik/operations/dashboard/">Traefik dashboard</a></td>
        <td>This was already installed with K3s, just exposing it with ingress and basic auth</a></td>
    </tr>
    <tr>
        <td><img vertical-align=baseline width="32" src="https://raw.githubusercontent.com/loganmarchione/svg-assets/main/assets/go-blue.svg"></td>
        <td><a href="https://hub.docker.com/r/traefik/whoami/">whoami</a> (<a href="https://github.com/traefik/whoami">source</a>)</td>
        <td>Tiny Go server that prints os information and HTTP request to output</td>
    </tr>
</table>

## Installation

See the [README](/scripts/README.md) for more information
