# Custom appstore

This is my appstore repository for runtipi

## Repository Structure

- **apps/**: Contains individual app directories

  - Each app has its own folder (e.g., `whoami/`) with the following structure:
    - `config.json`: App configuration file
    - `docker-compose.json`: Docker setup for the app
    - `metadata/`: Contains app visuals and descriptions
      - `description.md`: Markdown description of the app
      - `logo.jpg`: App logo image

- **tests/**: Contains test files for the app store

  - `apps.test.ts`: Test suite for validating apps

## Apps
	- `Dawarich`: A location tracker, good alternative for Google maps timeline
	- `Unifi`: Manage your unifi devices

## Documentation

This repository is based on the default template, to create your own, please refer to the official guide:
[Create Your Own App Store Guide](https://runtipi.io/docs/guides/create-your-own-app-store)
