# TLS Manager

TLS-enabled networking and certificate management for Open Integration Engine. The
plugin adds a **TLS Settings** section to supported connectors and a **certificate
management** view for issuing, importing, and managing the keystore material those
connectors use.

## Features

- **TLS settings for connectors** — configure TLS/mTLS directly on supported
  connector types from the channel editor.
- **Certificate management view** — manage the engine's keystore: import, generate,
  and inspect certificates and keys.
- **Mutual TLS (mTLS)** — present and verify client/server certificates.
- Ships a bundled web management UI alongside the engine plugin.

## Requirements

- Open Integration Engine **4.5.2** or newer.
- An engine restart after install to activate the plugin and its connectors.

## Installing

Install from the Community Store, then **restart the engine**. After the restart the
TLS Settings appear on supported connectors and the TLS Manager view becomes
available in the administrator.

## Configuration & usage

See the [project README](https://github.com/NovaMap-Health/tls-manager-plugin#readme)
for keystore setup, connector TLS options, and the certificate management workflow.

## License

Dual-licensed **Apache-2.0** / **MPL-2.0**. Original project by NovaMap Health.

## Support

Report issues at
[github.com/NovaMap-Health/tls-manager-plugin/issues](https://github.com/NovaMap-Health/tls-manager-plugin/issues).
