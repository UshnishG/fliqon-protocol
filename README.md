# Fliqon Protocol

The open specification of the protocol Fliqon uses to send files from a phone to a PC over a local network:
pairing by QR code with TLS certificate pinning, HMAC-SHA256 request signing with replay protection,
streamed and resumable uploads with SHA-256 verification, batch announcements, and local discovery
(mDNS + UDP beacon).

- **Specification:** [`PROTOCOL.md`](PROTOCOL.md)
- **Get Fliqon:** [Early Access Programme](https://fliqon.vercel.app)

## Licence

The specification is licensed under [CC BY 4.0](LICENSE): you may share and adapt it, including to build
compatible implementations, as long as you give appropriate credit.

The Fliqon apps themselves are proprietary and are not covered by this licence.
