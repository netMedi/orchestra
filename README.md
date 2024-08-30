# orchestra

Convenient way to orchestrate containers.


## Prepare secrets

```sh
PROFILE=my-profile-name pnpm s:secrets:prepare

# OR
pnpm s:secrets:prepare my-profile-name

# OR (to prepare all profiles)
pnpm s:secrets:prepare --all
```

## Run project commands

```sh
PROFILE=my-profile-name pnpm Holvikaari:db:start
```
