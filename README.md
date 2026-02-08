# Privacy-DNS-Compose-Stack

A docker/podman container stack combining **AdGuard Home**,
**Unbound**, **Valkey**, and **DNSCrypt-Proxy**.

## First Steps

Be sure to copy _`./adguardhome/conf/AdGuardHome.base.yaml`_ to
_`./adguardhome/conf/AdGuardHome.yaml`_ before using either
`docker-compose` or `podman compose`.

> [!NOTE]
> It's better to stick with rootful Docker since you are
> less likely to bump into issues. This does not work well
> with rootful/rootless Podman.

## License

This project is licensed under the **Unlicense** license.
