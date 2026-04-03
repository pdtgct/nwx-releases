# Network Weather Releases

This repository contains packaged distributions of the Network Weather desktop app for macOS and Windows.

Network Weather is a network diagnostics app focused on problems that show up as choppy video calls, dropped connections, weak Wi-Fi, VPN slowdowns, and similar issues. Per the official site, it helps identify whether the problem is your computer, Wi-Fi, router/LAN, ISP, VPN, or the online service itself, then presents the result in plain English with suggested fixes.

This repository is for release artifacts, not the main product site or primary source-code home.

## Official Links

- Product website: [networkweather.com](https://networkweather.com)
- Documentation: [networkweather.com/docs](https://networkweather.com/docs/)
- GitHub organization: [github.com/Network-Weather](https://github.com/Network-Weather)

## What This Repository Contains

- macOS installer packages in [`releases/macos`](./releases/macos)
- Windows installer packages in [`releases/windows`](./releases/windows)
- SHA-256 checksum files alongside installers where available
- Release notes for published builds

## Repository Layout

```text
releases/
  macos/
    *.pkg
    *.sha256
    *-release-notes.txt
  windows/
    *.msix
    *.sha256
    *-release-notes.txt
```

## Notes

- If you want to download and use Network Weather, start with the official website.
- If you want documentation, deployment guidance, or API details, use the docs site.
- If you are looking for source repositories, SDKs, or related development work, see the official GitHub organization.
