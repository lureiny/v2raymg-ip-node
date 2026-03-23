# v2ryamg-ip-node

Auto-updated probe node lists for [v2raymg](https://github.com/lureiny/v2raymg).

## Files

- **`icmp_nodes.yaml`** — ICMP probe nodes. Each entry contains `host`, `geo`, `isp`, and `usage: [icmp]`. Used by v2raymg for ICMP latency detection.

- **`tcp_nodes.yaml`** — TCP probe nodes. Each entry contains `host`, `port`, `geo`, `isp`, and `usage: [tcp]`. Used by v2raymg for TCP connectivity detection.

Both files are automatically refreshed every hour via GitHub Actions.
