# home-stats-node
Infrastructure for stats collection of a node at home.

Telegraf is used to push stats to an influx database.

## Prerequisites
* docker-compose

# Usage
* Copy `telegraf_env_example` to `telegraf.env` and modify
* Modify `mytelegraf.conf`
* `docker-compose up -d`
