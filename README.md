# Learning with Texts

[![Latest Stable Version](https://poser.pugx.org/ProgramComputer/lwt/v)](https://packagist.org/packages/ProgramComputer/lwt)
[![Docker Image](https://github.com/ProgramComputer/lwt/actions/workflows/docker-image.yml/badge.svg)](https://github.com/ProgramComputer/lwt/actions/workflows/docker-image.yml)
[![Discord Server](https://badgen.net/discord/members/zAE8GXMKFa?icon=discord)](https://discord.gg/zAE8GXMKFa)

**Learning with Texts** (LWT) is a tool for language learning by reading.
This repository is a Docker installer, the main repository can be found at
<https://github.com/ProgramComputer/lwt>.

[![LWT logo](https://github.com/ProgramComputer/lwt/raw/youtube-dl/img/lwt_icon_big.jpg)](https://github.com/ProgramComputer/lwt)

## Prerequisites

This is a Docker installer, we recommand to use
[Docker Desktop](https://docs.docker.com/desktop/) for any unexperienced user.

Formally, you only need:

* [Docker](https://www.docker.com/)
* [Docker Compose](https://docs.docker.com/compose/install/) plugin

## Installation

For copy/pasters:

```bash
git clone https://github.com/ProgramComputer/lwt-docker-installer # download this repository
cd lwt-docker-installer
cp .env.sample .env                                        # don't hesitate to edit .env!
docker compose up -d
```

Manual instructions:

1. Copy the repository [ProgramComputer/lwt-docker-installer](https://github.com/ProgramComputer/lwt-docker-installer)
2. Create the ``.env`` file and customize it to your convenience
3. Run ``docker compose up -d``

By default the server can be accessed on port 8010 (<http://localhost:8010>).

## Remove

To remove the created containers go the the created folder and run:

```bash
docker compose down
```

## Data storage

All user data will be stored in local folder `./lwt_db_data`.

**Let's learn new languages!**
