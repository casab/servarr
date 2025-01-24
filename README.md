# Servarr

## Description

This project is a Docker-based media management application utilizing Plex.

### Features

Following services are used:

- Plex
- Radarr
- Sonarr
- Bazarr
- Prowlarr
- FlareSolverr
- Overseerr
- Tautulli
- QBitTorrent
- Watchtower

## Installation

1. Clone the repository.
2. Ensure Docker and Docker Compose are installed on your machine.
3. Fill out .env file
4. Run `docker-compose up -d` to start the services.

## Usage

Access the Plex media server at `http://localhost:32400`.

## Configuration

Edit the `.env` and `docker-compose.yaml` files to customize your setup, including volume mappings and environment variables.

- If you have an AMD graphics card and if you are not on Windows, you may want to remove the comment on `USE_AMD_PLEX_IMAGE` in the .env file.
