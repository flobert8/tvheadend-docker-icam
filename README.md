# TVHeadend ICAM + Vue Web UI

A custom Docker/OCI image of TVHeadend featuring **ICAM support** and the **modern Vue.js web interface**, built automatically using GitHub Actions.

Based on [upchui/tvheadend-docker-icam](https://github.com/upchui/tvheadend-docker-icam), with additional Vue UI build support.

## Features

- **TVHeadend 4.3** – Built from upstream source
- **ICAM Support** – Preserves the ICAM-related modifications from the original project
- **Vue Web UI** – Modern web interface compiled directly from source
- **GitHub Actions** – Automated AMD64 container image builds
- **GitHub Container Registry** – Images published via GHCR
- **Proxmox VE OCI** – Successfully deployed as a Proxmox OCI container
- **Docker Compatible** – Can also be used with Docker and Docker Compose

## Container Image

```text
ghcr.io/flobert8/tvheadend-docker-icam:vue
```

## Web Interface

After starting the container, open:

```text
http://YOUR-SERVER-IP:9981/gui/
```

The classic ExtJS interface remains available at `/extjs.html`.

## Credits

This project is based on [upchui/tvheadend-docker-icam](https://github.com/upchui/tvheadend-docker-icam) and the work of the [TVHeadend](https://github.com/tvheadend/tvheadend) and [LinuxServer.io](https://www.linuxserver.io/) communities.

## Disclaimer

This is an unofficial, community-maintained fork primarily intended for personal homelab use. It is not affiliated with or officially supported by the original projects.
