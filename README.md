# DaVROS CTF, "Low Battery"

```sh
TEAM_SEED=team-01 docker compose up -d           # start
docker compose exec player bash                  # the player's shell
docker compose down -v                           # reset
```

Operator display on http://localhost:8090. `TEAM_SEED` changes the flag.
