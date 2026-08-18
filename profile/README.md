<h1 align="center"> 1995parham.me </h1>
<h6 align="center"> The servers, services, and glue that keep my domain and my home running </h6>

<p align="center">
  <img src="https://raw.githubusercontent.com/1995parham-me/.github/main/profile/img/me.png" alt="me" height="250px" />
</p>

## Introduction

This is the home of everything that runs *behind* [1995parham.me](https://1995parham.me): the self-hosted
services on my home boxes, the small pieces of automation that set my machines up, and the monitoring that
tells me how they are all doing.

Nothing here is a framework or a product. Each repository is a `docker-compose.yaml`, a `justfile`, or a
handful of scripts — deliberately small, so that re-deploying a service after a disk dies is a matter of
`git clone` and one command. If you self-host at home, most of these are copy-paste friendly.

> [!NOTE]
> Application code lives on my personal account, [@1995parham](https://github.com/1995parham).
> This organization is infrastructure only.

## Self-Hosted Services

Things I actually run at home, each with the configuration needed to bring it back from scratch.

| Repository | What it is |
| --- | --- |
| [copyparty](https://github.com/1995parham-me/copyparty) | Portable file server with resumable uploads, WebDAV, and a web dashboard |
| [samba](https://github.com/1995parham-me/samba) | SMB shares on Arch Linux, for the devices that never liked WebDAV |
| [nextcloud](https://github.com/1995parham-me/nextcloud) | Nextcloud All-in-One on a small embedded server, behind Caddy |
| [xandikos](https://github.com/1995parham-me/xandikos) | CalDAV/CardDAV server that keeps my calendar and contacts in plain git repositories |
| [swagger](https://github.com/1995parham-me/swagger) | Swagger Editor at `127.0.0.1`, because the hosted one is not reachable from Iran |

## Automation & Tooling

| Repository | What it is |
| --- | --- |
| [ansible-role](https://github.com/1995parham-me/ansible-role) | The `parham_alvani.dotfiles` Ansible collection that installs my [dotfiles](https://github.com/1995parham/dotfiles) and their dependencies |
| [docker](https://github.com/1995parham-me/docker) | A debugging image full of networking tools, for when a Kubernetes pod misbehaves — `ghcr.io/1995parham-me/docker` |
| [prometheus](https://github.com/1995parham-me/prometheus) | Prometheus and Node Exporter watching the low-cost nodes at home |

## Archived

Kept for reference, no longer maintained.

| Repository | What it was |
| --- | --- |
| [domjudge-role](https://github.com/1995parham-me/domjudge-role) | Ansible role that installed [DOMjudge](https://www.domjudge.org/), the programming-contest judge system, on a fresh machine |

## License

Every repository in this organization is released under the [GNU General Public License v3.0](https://github.com/1995parham-me/.github/blob/main/LICENSE).
