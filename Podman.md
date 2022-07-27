# Podman

## Container

## Machine

**References**

[podman-machine — Podman documentation](https://docs.podman.io/en/latest/markdown/podman-machine.1.html)

#### Initialize

```
podman machine init --cpus=4 --disk-size=16 --memory=2048 --rootful --volume=/host-dir:/machine-dir machine-name
```

> Memory size over 2048 MB may cause some problem when creating the VM. (bug?)

#### Start

```
podman machine start machine-name
```

#### Stop

```
podman machine stop machine-name
```

#### Remove

```
podman machine rm machine-name
```

