## GitHub Copilot Chat

- Extension: 0.49.0 (prod)
- VS Code: 1.121.0 (f6cfa2ea2403534de03f069bdf160d06451ed282)
- OS: win32 10.0.19045 x64
- GitHub Account: Princesg-1506

## Network

User Settings:

```json
  "http.systemCertificatesNode": true,
  "github.copilot.advanced.debug.useElectronFetcher": true,
  "github.copilot.advanced.debug.useNodeFetcher": false,
  "github.copilot.advanced.debug.useNodeFetchFetcher": true
```

Connecting to https://api.github.com:

- DNS ipv4 Lookup: 140.82.121.5 (78 ms)
- DNS ipv6 Lookup: Error (34 ms): getaddrinfo ENOTFOUND api.github.com
- Proxy URL: None (2 ms)
- Electron fetch (configured): HTTP 200 (596 ms)
- Node.js https: HTTP 200 (603 ms)
- Node.js fetch: HTTP 200 (797 ms)

Connecting to https://api.individual.githubcopilot.com/_ping:

- DNS ipv4 Lookup: 140.82.113.22 (58 ms)
- DNS ipv6 Lookup: Error (108 ms): getaddrinfo ENOTFOUND api.individual.githubcopilot.com
- Proxy URL: None (92 ms)
- Electron fetch (configured): HTTP 200 (868 ms)
- Node.js https: HTTP 200 (920 ms)
- Node.js fetch: HTTP 200 (968 ms)

Connecting to https://proxy.individual.githubcopilot.com/_ping:

- DNS ipv4 Lookup: 20.250.119.64 (61 ms)
- DNS ipv6 Lookup: Error (33 ms): getaddrinfo ENOTFOUND proxy.individual.githubcopilot.com
- Proxy URL: None (39 ms)
- Electron fetch (configured): HTTP 200 (621 ms)
- Node.js https: HTTP 200 (743 ms)
- Node.js fetch: HTTP 200 (686 ms)

Connecting to https://mobile.events.data.microsoft.com: HTTP 404 (340 ms)
Connecting to https://dc.services.visualstudio.com: HTTP 404 (953 ms)
Connecting to https://copilot-telemetry.githubusercontent.com/_ping: HTTP 200 (981 ms)
Connecting to https://telemetry.individual.githubcopilot.com/_ping: HTTP 200 (1147 ms)
Connecting to https://default.exp-tas.com: HTTP 400 (851 ms)

Number of system certificates: 103

## Documentation

In corporate networks: [Troubleshooting firewall settings for GitHub Copilot](https://docs.github.com/en/copilot/troubleshooting-github-copilot/troubleshooting-firewall-settings-for-github-copilot).
