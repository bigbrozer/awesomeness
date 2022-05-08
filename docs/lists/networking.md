---
tags:
  - system-network
---

# Networking

<div align="center">
    <a href="https://awesome.re">
        <img src="https://awesome.re/badge.svg" alt="Awesome">
    </a>
</div>

* * *

## Distributions

- [opnsense](https://opnsense.org/) — An open source, easy-to-use and easy-to-build FreeBSD based firewall and routing platform.

## Misc

![5e84bd9d64bd9cc3b642d118651431c6.png](../assets/5e84bd9d64bd9cc3b642d118651431c6.png)

## MTU discovery

```bash
for i in `seq 1460 1500`; do ping -c1 -s $i -M do 1.1.1.1; sleep 0.1; done
```

## Overlay networks

- [nebula](https://github.com/slackhq/nebula) — A scalable overlay networking tool with a focus on performance, **simplicity** and security.

## Tunnel

- [pritunl](https://github.com/pritunl/pritunl) — A distributed enterprise vpn server built using the OpenVPN protocol.

- [tunnelmon](https://github.com/nojhan/tunnelmon) — An (auto)ssh tunnel monitor. It gives a user interface to monitor existing SSH tunnels, and tunnels that are managed with autossh.

## Virtual Networks

- [netmaker](https://github.com/gravitl/netmaker) — Makes networks with WireGuard. Automates fast, secure, and distributed virtual networks.
