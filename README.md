# Subnet Studio

A standalone IPv4 subnet calculator. Open `index.html` in a browser; there is no build step, package install, or backend.

## Features

- Enter an IPv4 address and CIDR prefix, or paste a value such as `192.168.1.42/24`.
- See the network address, subnet and wildcard masks, broadcast address, total address count, usable host count, and first and last host addresses update as you type.
- Inspect the IP address and subnet mask in binary, with network and host bits highlighted.
- Divide the current network into a longer prefix and preview the resulting subnet ranges.
- Copy the calculated network CIDR by clicking it.
- Try the included private-network presets.

All calculation code and styles are included in `index.html`. No values are sent to a server.

## Host-count conventions

For prefixes `/0` through `/30`, the network and broadcast addresses are excluded from the usable host count. A `/31` has two usable addresses for point-to-point links. A `/32` represents one address; its first and last address are that same address.
# Network-Subnet-Calculator
