## TestHR
TestHR Backend example work.

### Project Details
- Informations

### Get Started
- Informations

### Installation
- Informations

### Docker

- Dev mode setup.

```bash
$ cd docker
$ docker-compose --project-name testhr --env-file ./config/.env -f docker-compose.yml -f docker-compose.dev.yml up --build -d
```

- Release mode setup.

```bash
$ cd docker
$ docker-compose --project-name testhr --env-file ./config/.env up --build -d
```