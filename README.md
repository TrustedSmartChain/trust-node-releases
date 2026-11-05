# trust-node-releases

Release binaries for the TSC trust and nano nodes. See [Releases](https://github.com/TrustedSmartChain/trust-node-releases/releases).

Each release contains `trust_<version>_<os>_<arch>` and `nano_<version>_<os>_<arch>` binaries, the install scripts, and `checksums.txt`.

## Install

Run as root on Linux (amd64 or arm64). Download the script first, because activation prompts for a private key and needs a terminal:

```
curl -fsSLO https://github.com/TrustedSmartChain/trust-node-releases/releases/latest/download/install-trust.sh
sudo sh install-trust.sh -e mainnet
```

Use `install-nano.sh` for a nano node, or `linux-install-node-<validator|sentry|rpc|archive>.sh` for a chain node; run those with `--help` to see the required options.
