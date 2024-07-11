# Trying to understand FlyWay migrations

- On the first attempt i used just docker compose and 3 containers, 1 for the db, 1 for the baseline and another one for the migration.

- The second one was using kubernetes, but instead of passing sql files we just pass them in a config map
- 