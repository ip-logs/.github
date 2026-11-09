<p align="center">
  <img src="./logo.svg" width="88" height="88" alt="IPLogs logo">
</p>

<h1 align="center">IPLogs</h1>

<p align="center">
  <b>See what websites see.</b><br>
  Free VPN, proxy &amp; Tor &amp; datacenter IP detection — with the evidence behind every verdict.
</p>

<p align="center">
  <a href="https://iplogs.com">iplogs.com</a> ·
  <a href="https://iplogs.com/docs">API docs</a>
</p>

---

IPLogs tells you whether an IP address reads as a **VPN, proxy, Tor exit, privacy relay or datacenter** — and *why*. It runs **seven layers** of detection and returns a verdict and a **0–100 score with the matched signals**, not a black box.

### Try it — no sign-up, no key

```bash
curl iplogs.com/1.1.1.1
```

```json
{
  "ip": "1.1.1.1",
  "verdict": "clean",
  "score": 0,
  "is_vpn": false,
  "is_proxy": false,
  "is_tor": false,
  "is_relay": false,
  "is_hosting": false,
  "asn": "AS13335",
  "org": "Cloudflare, Inc.",
  "signals": []
}
```

### What you get

- **A verdict + score with evidence** — every signal that fired is listed, so you can see the reasoning.
- **Full coverage** — VPNs, proxies, Tor exits, privacy relays (iCloud Private Relay, Cloudflare WARP), and hosting/datacenter ranges.
- **IPv4 and IPv6.**
- **Free API** — no account, no key. 2,000 full checks per IP per day at up to 60 req/min; beyond that, answers still come from the fast in-memory path.

### Privacy by default

No database of lookups. No tracking cookies. No ads. Web-server access logs are kept 30 days for abuse prevention, then deleted.

---

<p align="center"><sub>A <a href="https://digitald.tech">DigitalD.tech</a> project.</sub></p>
