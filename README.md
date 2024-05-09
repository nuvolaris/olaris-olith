# NUVOLITH

## Requirements

- nuv cli
- docker-compose.yml saved in your NUV_PWD directory
- (project dependencies)*

## Quickstart

### configure your environment and customize the HOSTNAME value

```bash
cp .env.sample .env
```
### customize ingress options

edit the file deploy/olith-ingress.yaml or create other components

### deploy

```bash
nuv olith deploy
```

### undeploy
```bash
nuv olith undeploy
```
### show configuration
```bash
nuv olith config:show
```
