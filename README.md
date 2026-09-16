# Hey, I'm Kampai 👋

1988-born dude, anime fan, and hands-on tinkerer building practical Linux, Windows, wireless, and security tools.

My projects cover packet inspection, wireless inventory, adapter deployment, connection management, and Raspberry Pi automation. I like turning fragile setup notes into repeatable installers, diagnostics, and small utilities that are easier to trust and maintain.

## Featured projects

### [Packet Inspector — Kali/Linux](https://github.com/KampaiDiscount/packet-inspector)

Live capture and offline PCAP analysis for authorized network audits, with TCP stream reconstruction, sensitive-field detection, capture-loss visibility, and a local dashboard. Available as a **test prerelease** with a source package, Python wheel, and checksums; use the Kali installer for host setup.

### [Packet Inspector — Windows](https://github.com/KampaiDiscount/packet-inspector-windows)

A native Windows edition with Npcap capture, stream-aware auditing, private exports, and a loopback dashboard. Available as a **test-release ZIP** with launchers and an offline Python wheel; Python, Wireshark/dumpcap, and Npcap are separate prerequisites. See the repository for validation boundaries and setup instructions.

### [Install the ALFA AWUS1900 Driver on Kali Linux](https://github.com/KampaiDiscount/kali-awus1900-deploy)

A one-command ALFA AWUS1900 / RTL8814AU driver installer and recovery tool for Kali Linux, with DKMS rollback, native-driver fallback, diagnostics, and reversible monitor-mode helpers.

### [AWUS1900 Surveyor](https://github.com/KampaiDiscount/awus1900-surveyor)

An autonomous passive 2.4/5 GHz access-point inventory tool for the ALFA AWUS1900 on Kali Linux. Tracks signal and advertised security details, checkpoints results, and produces offline HTML, CSV, JSON, and Markdown reports.

### [WiFi Pineapple Mark VII Connection Manager](https://github.com/KampaiDiscount/Pineapple-MarkVII-Connection-Manager)

Separate Windows and Debian/Linux host connection managers for USB monitoring, Internet sharing, repair, diagnostics, and opening the Pineapple web interface. Windows uses Internet Connection Sharing; Linux uses scoped nftables NAT and optional systemd monitoring.

## Packages and downloads

| Project | Platform | Get it |
| --- | --- | --- |
| Packet Inspector | Kali/Linux | [Test-release source package, wheel and checksums](https://github.com/KampaiDiscount/packet-inspector/releases/tag/v0.1.4) |
| Packet Inspector for Windows | Windows | [Test-release ZIP and checksum](https://github.com/KampaiDiscount/packet-inspector-windows/releases/tag/v0.1.4-win.1) |
| AWUS1900 driver installer | Kali Linux | [Standalone installer and checksum](https://github.com/KampaiDiscount/kali-awus1900-deploy/releases/latest) |
| AWUS1900 Surveyor | Kali Linux | [ZIP / tar.gz and checksums](https://github.com/KampaiDiscount/awus1900-surveyor/releases/latest) |
| Pineapple Connection Manager | Windows 10/11 | [Windows ZIP and checksum](https://github.com/KampaiDiscount/Pineapple-MarkVII-Connection-Manager/releases/tag/v3.2) |
| Pineapple Connection Manager | Debian/Linux | [Debian package / tar.gz and checksums](https://github.com/KampaiDiscount/Pineapple-MarkVII-Connection-Manager/releases/tag/linux-v0.1.0) |
| Raspberry Pi SIM800C tools | Raspberry Pi OS / Linux | [Alpha source archives and checksums](https://github.com/KampaiDiscount/Tools/releases/tag/v0.1.0-alpha.1) |

## More tinkering

[Raspberry Pi SIM800C deployment](https://github.com/KampaiDiscount/Tools) — cellular PPP and ngrok SSH access in an isolated network namespace, with automatic health checks and recovery. **Source-only alpha** under the MIT license; hardware and carrier validation remain deployment-specific.

> Security and wireless tooling should be used only on systems and networks you own or are explicitly authorized to assess.
