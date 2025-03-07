# Mailcatcher

Mailcatcher for local development or testing environment.

## Usage

Clone this repository:
```shell
git clone https://github.com/erkenes/docker-mailcatcher.git
```

Copy the `.env.example` file to `.env`:
```shell
cp .env.example .env
```

Edit the `.env` file and provide values for the environment variables as needed.

- `MAILCATCHER_DOMAIN`: The domain name for the Mailcatcher web interface.


Start Mailcatcher by running:
```shell
docker compose up -d
```
