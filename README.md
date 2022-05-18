# fluentbit-forwarder

A project to run Fluent Bit in forward mode.

## Project structure

---

```bash
/opt/
 📦fluentbit-forwarder
 ┣ 📂conf                   - directory config files fluentbit.
 ┣ 📜.env_template          - environment template file.
 ┣ 📜.gitignore
 ┣ 📜README.md
 ┗ 📜docker-compose.yaml    - Docker-compose project.
 ┗ 📜docker-compose-template.yaml    - Docker-compose file template.
 ```

## Pre-deployment preparation

---

Before deploying the project, install Docker, Docker Compose latest versions.

---

## Installation

---

For installation:
To install, run:

1. Do a git clone.

2. Create an .env file and fill with variables:

```bash
cp ./.env_temp ./.env

```

3. Run the project

```bash
docker-compose up -d

```

4. After a couple of minutes, the service will start.

---

### Useful links

---

[Fluent Bit: Official Manual](https://docs.fluentbit.io/manual)
