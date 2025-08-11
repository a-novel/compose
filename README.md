# Compose

Global compose file to run the application locally.

## Prepare

Create a `.envrc` file from the template:

```bash
cp .envrc.template .envrc
```

Then fill the missing secret variables. Once your file is ready:

```bash
source .envrc
```

> You may use tools such as [direnv](https://direnv.net/), otherwise you'll need to source the env file on each new
> terminal session.

## Run

```bash
podman compose -p agora up -d
```

## Stop

```bash
podman compose -p agora down
```
