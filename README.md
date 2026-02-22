# Privacy-DNS-Compose-Stack

A docker/podman container stack combining **AdGuard Home**,
**Knot Resolver**, and **DNSCrypt-Proxy**.

## First Steps

1. Copy _`./adguardhome/conf/AdGuardHome.base.yaml`_ to
_`./adguardhome/conf/AdGuardHome.yaml`_ before using either

2. Run `./knot/generate-config` to generate a brand new yaml
config for the _**Knot Resolver**_. Which will be located
at `./knot/config.yaml`.

Afterwards, run either `sudo docker-compose up -d` or
`sudo podman-compose up -d`.

> [!NOTE]
> It's better to stick with rootful Docker since you are
> less likely to bump into issues. This does not work well
> with rootful/rootless Podman.

## Logging in to AdGuard Home WebUI

The username is: **root** <br>
The password is: **rootpass**

## License

This project is licensed under the **Unlicense** license.
