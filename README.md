# UptimeCast

**Self-hosted live streaming server with automatic failover.** Your live stream stays on air.

UptimeCast delivers your own live channels (church services, events, in-house hotel channels, local TV) to smart TVs, set-top boxes, phones and computers. Add several feeds to each channel: if the main one drops, UptimeCast switches to a backup in about a second, shows a standby screen instead of black, and goes back to the best feed by itself.

Website: **[uptimecast.com](https://uptimecast.com)** (available in 10 languages)

## Download

**Latest version: 0.12.2** — [uptimecast-0.12.2-linux.tar.gz](https://github.com/migosu/uptimecast-releases/raw/main/downloads/uptimecast-0.12.2-linux.tar.gz) ([sha256](downloads/uptimecast-0.12.2-linux.tar.gz.sha256)) · [release notes](https://github.com/migosu/uptimecast-releases/releases/tag/v0.12.2)

The same package is also at [uptimecast.com](https://uptimecast.com/download/uptimecast-linux.tar.gz).

## Install (about two minutes)

Ubuntu 22.04, 24.04 or 26.04, or Debian 11 to 13 (amd64 or arm64).

```bash
curl -LO https://github.com/migosu/uptimecast-releases/raw/main/downloads/uptimecast-0.12.2-linux.tar.gz
tar xzf uptimecast-0.12.2-linux.tar.gz
cd uptimecast-0.12.2
sudo ./install.sh
```

The installer asks your language first, shows what it will do before doing it, and never touches the services you already have. Run it again with a newer package to upgrade: your configuration, channels and database are kept.

When it finishes, open the panel with the address and password it shows you.

## What it does

- **Automatic failover:** several feeds per channel; a backup takes over in about a second.
- **Always the best quality:** plays the highest-definition feed that works and returns to it when it is stable.
- **Adaptive quality:** each viewer's player picks the quality their connection can hold, without transcoding.
- **Program guide (EPG):** add your XMLTV guide and it is matched to your channels.
- **Works on the devices your viewers have:** M3U playlists, XMLTV and the Xtream Codes API (smart TVs, set-top boxes, VLC, Kodi, mobile apps).
- **Protected playback links:** signed, per-viewer links that stop working when shared.
- **Light on your server:** streams pass through without transcoding.
- **Panel in 10 languages:** English, Spanish, French, Portuguese, Arabic, Turkish, German, Italian, Russian and Chinese.
- **Moving from Xtream UI or XUI.one?** The panel imports your channels and sources from a database dump.

## Who it's for

Churches and houses of worship, live events and conferences, hotels, venues and campuses, and local and community TV.

## Plans

| Plan | Price | Includes |
| --- | --- | --- |
| Free | $0 | 10 channels, 50 simultaneous viewers, 1 server, no time limit |
| Starter | $19/month | 100 channels, 1,000 viewers, partner sub-accounts, 1 server |
| Pro | $39/month | Unlimited channels and viewers, up to 3 servers |
| Business | $79/month | Unlimited, up to 10 servers, white label (your name and logo), priority support |
| Pro for life | $399 once | Everything in Pro, no renewals |

Yearly plans include two months free. Details at [uptimecast.com/#pricing](https://uptimecast.com/#pricing).

## License and content

UptimeCast is proprietary software, free to use on the Free plan; paid plans need a license key. This repository only publishes the installable packages; the source code is not public.

UptimeCast is software only. It includes no channels or content. Use it only with content you produce or have the rights to distribute. Xtream Codes is a trademark of its respective owners; UptimeCast is only compatible with its API.

## Support

Write to **sales@uptimecast.com**.
