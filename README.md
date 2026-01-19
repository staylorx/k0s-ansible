# ansible-control

## Push keys/apt update

```bash
poetry run ansible-playbook push-keys.yaml -u k0s
```

## Reset/remove k0s

```bash
poetry run ansible-playbook reset.yml -u k0s
```

## Install k0s

```bash
poetry run ansible-playbook site.yml -u k0s
```

## Check it out

Assumes k9s is what you're using here:

```bash
k9s --kubeconfig tools/artifacts/k0s-kubeconfig.yml
```
