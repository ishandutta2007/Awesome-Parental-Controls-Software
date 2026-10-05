# Awesome-Parental-Controls-Software

## Top Parental Controls Software Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Content Filtering, Screen Time Management & Digital Wardship*  

**Last updated: October 2026**



This repository tracks notable **commercial parental control platforms** and **open-source projects** that help families manage children's device usage — from content filtering and screen time limits to app blocking and location monitoring.



**Examples** include Microsoft Family Safety, Qustodio, Bark, Net Nanny, Norton Family, Kaspersky Safe Kids, OurPact, Circle Home Plus, Google Family Link, and Mobicip (the category leaders).



**Open-source emphasis**: Parental controls is a domain where open-source provides meaningful alternatives. **WiFiHaven** offers network-level monitoring and control, **kids-control** provides one-command Linux PC protection, and **Kintrinsic** pioneers "digital wardship" with local-first key management. **AdGuard Home** and **Pi-hole** deliver DNS-level filtering with family-safe options built in. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Qustodio](https://www.qustodio.com/)**  

  Comprehensive parental control suite with web filtering, app blocking, screen time limits, and location tracking. **The market leader for cross-platform controls**.



- **[Bark](https://www.bark.us/)**  

  AI-powered monitoring that alerts parents to concerning messages without reading everything. **Best for detecting cyberbullying, self-harm, and predators**.



- **[Net Nanny](https://www.netnanny.com/)**  

  Content filtering specialist with real-time analysis and family protection. **Best for web content filtering**.



- **[Norton Family](https://us.norton.com/family)**  

  Norton's parental controls with web supervision, time management, and location tracking.



- **[Kaspersky Safe Kids](https://www.kaspersky.com/safe-kids)**  

  Comprehensive parental controls with GPS tracking, app management, and web filtering.



- **[OurPact](https://ourpact.com/)**  

  Screen time management and app blocking with easy scheduling.



- **[Circle Home Plus](https://meetcircle.com/)**  

  Network-level parental controls via hardware device — filters all devices on the home network.



- **[Google Family Link](https://families.google.com/familylink/)**  

  Free parental controls for Android and Chromebook — screen time, app approval, and location sharing.



- **[Mobicip](https://www.mobicip.com/)**  

  Cross-platform parental controls with web filtering and screen time management.



- **[Microsoft Family Safety](https://www.microsoft.com/en-us/microsoft-365/family-safety)**  

  Free parental controls for Microsoft ecosystem — screen time, app limits, and family location sharing.



## Open-Source GitHub Projects



### Network-Level Filtering



- **[WiFiHaven](https://github.com/wifihaven/wifihaven)**  

  **Open-source service to monitor and control children's internet usage at home**, MIT licensed . **DNS enforcement and usage tracking run on gateway router** (OpenWRT/OPNsense agent) with API and PostgreSQL backend via Docker Compose . **The best open-source network-level parental control** — covers all devices on the network without per-device software . **Best for families wanting network-wide filtering with self-hosted data** .



- **[AdGuard Home](https://github.com/AdguardTeam/AdGuardHome)**  

  **Open-source network-wide DNS filtering with built-in parental controls**, GPL-3.0 licensed . **Parental control, Safe Search, and Safe Browsing included by default** . **Single binary, cross-platform** (Linux, Windows, macOS, FreeBSD) . **Client management with per-device rules** . **The best DNS filtering solution for families** — encrypted DNS (DoH, DoT, DoQ) built in . **Trade-off**: smaller community than Pi-hole, query log less detailed  . **Best for families wanting easy setup with family-safe features** .



- **[Pi-hole](https://github.com/pi-hole/pi-hole)**  

  **The most widely adopted network-wide ad blocker**, EUPL licensed . **Blocks ads and trackers for all devices** . **Note**: **no built-in parental controls or Safe Search** — requires additional configuration  . **Best for privacy-focused families** willing to configure additional filtering.



- **[blocklistproject/Lists](https://github.com/blocklistproject/Lists)**  

  **Curated collection of DNS blocklists for network content filtering**, MIT licensed . **Category-specific blocklists** for adult, gambling, and drug content . **Supports Pi-hole, AdGuard Home, and other DNS filters**  . **Best for supplementing DNS filtering with categorized blocklists** .



- **[Rethink App](https://github.com/celzero/rethink-app)**  

  **Network security tool providing application firewall and DNS blocklist manager**, MPL-2.0 licensed . **Blocks website categories like gambling or adult content** using curated DNS blocklists . **VPN client with multi-hop capabilities**  . **Best for per-device control on Android** .



### Device-Level Controls



- **[kids-control](https://github.com/ptskn/kids-control)**  

  **One-command parental controls for a child's Linux PC** (Debian/Ubuntu family), GPL-3.0 licensed . **Blocks TikTok, YouTube Shorts, and social networks** — forces SafeSearch, family DNS, and manages screen time . **Multi-layer enforcement**: Firefox policies, hosts file, Cloudflare Family DNS, and Timekpr-nExT . **Plain system mechanisms a child account cannot undo**  . **Remote manager UI** for editing blocklists over SSH . **Best for Linux families wanting robust, hard-to-bypass controls** .



- **[Kintrinsic](https://github.com/forgesworn/kintrinsic)**  

  **Libre, self-hosted digital wardship** — screen-time, app, content, and comms limits on a family's own keys, enforced on-device, no platform account . **Guardian grants scoped, revocable permissions signed with family keys** — Nostr-based protocol, no server holds family data . **Android Device Owner enforcer and Linux warden (charterd)** . **Explicitly designed as "wardship, not surveillance"** — transparent limits trending toward autonomy  . **Best for privacy-focused families wanting local-first, key-controlled enforcement** .



- **[LiFE Parental Control](https://github.com/valueerrorx/LiFE-Parental-Control)**  

  **Desktop parental control app for Linux** (KDE Plasma, GNOME), Electron/Vue 3 stack . **Web filter with custom domains + HaGeZi blocklists**, DNS-based filtering via dnsmasq, optional DoH hardening via iptables . **Screen time with daily limits and allowed hours** — quick presets for school/holiday . **App blocking with process killing**, per-app quotas with exemptions . **Dashboard with live usage** and activity log  . **Best for Linux families wanting a GUI-based parental control app** .



- **[Focusd](https://github.com/0xarchit/Focusd)**  

  **Free, open-source screen time tracker for Windows**, MIT licensed . **Monitors app usage, tracks browser tabs, sets daily limits** . **No cloud, no accounts** — SQLite storage locally . **CLI/TUI interface** with Pomodoro timer and app limits  . **Best for Windows users wanting self-managed screen time tracking** .



### Browser Extensions



- **[K9 Web Protection](https://github.com/khaleel-git/K9-Web-Protection)**  

  **Free, open-source content blocker for Chrome**, open-source . **Blocks porn and adult content** with built-in database of 70+ domains . **Social media blocker and Focus Mode** — 100% private, everything runs locally, no accounts, no tracking  . **Best for simple browser-level content blocking** .



- **[NetGuardian](https://addons.mozilla.org/firefox/addon/netguardian-esp/)**  

  **Firefox extension with parental control**, MIT licensed . **Blocks social media, video, gambling, and adult content** . **Parental control with PIN, usage statistics, tracker detection**  . **Best for Firefox users wanting simple browser-level controls** .



### Specialized Solutions



- **[Qualm](https://github.com/RoderickQiu/qualm)**  

  **First screen-time app built on Kev and Jev**, local-first on Apple silicon Macs . **Blocks the mechanism (Shorts, feeds, livestreams), not the site or app** — YouTube lecture stays; Shorts get a pop-up . **Rules are sentences, not site lists**: "short videos made for endless swiping" catches unlisted sites  . **Best for Mac users wanting intelligent, mechanism-level blocking** .



- **[WA Kids Filter](https://chromewebstore.google.com/detail/wa-kids-filter-%E2%80%94-parental/gknblnnlmpmcpdejohnlbdcdgjamfbic)**  

  **Open-source WhatsApp Web chat filter**, open-source . **Parents restrict which conversations are visible** — controlled from self-hosted PHP admin server . **No cloud, no third parties**  . **Best for parents wanting WhatsApp Web chat restrictions** .



### Additional Strong Open-Source Options



- **Swaybeing** — Per-app screen time tracker for Sway/i3 Linux, SQLite storage  .

- **Emby** — Self-hosted media server with content restrictions and viewing schedules for children  .

- **Cerbos** — Policy-as-code authorization with parent-child permission hierarchy  .



**Frameworks for building custom parental control solutions**: Combine **AdGuard Home** for easy DNS-level filtering with built-in parental controls and Safe Search  . Use **WiFiHaven** for network-wide monitoring with self-hosted API . Deploy **kids-control** for hard-to-bypass Linux PC protection . Choose **Kintrinsic** for local-first, key-controlled digital wardship . Use **Qualm** for intelligent mechanism-level blocking on Mac . Integrate **blocklistproject/Lists** for categorized DNS blocklists . Note that true commercial parental controls with AI-powered content analysis (Bark), cross-platform coverage, and location tracking remain primarily commercial territory; open-source stacks provide strong DNS filtering, screen time, and device-level controls that require configuration for complete family protection.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Parental control tools monitor children's device usage and may collect sensitive data. **Review privacy policies** — commercial tools may upload data to cloud servers; open-source local-first tools keep data on your infrastructure .

- **No parental control is 100% effective** — children can bypass controls via VPNs, alternative browsers, or device factory resets . Layer multiple controls for defense in depth .

- **Open-source parental controls vary significantly in maturity** — WiFiHaven and kids-control are production-ready; Kintrinsic is under active development  . Evaluate before relying on them as sole protection.

- **AdGuard Home has built-in parental controls and Safe Search; Pi-hole does not** — Pi-hole requires additional configuration for family-safe filtering  .

- The open-source ecosystem provides strong DNS filtering, screen time, and device-level controls, but **AI-powered content analysis, cross-platform coverage, and location tracking** remain primarily commercial offerings.



---



**Made for parents, guardians, and families seeking digital safety sovereignty.**  

Let's make parental controls more open, transparent, and respectful of family privacy.
