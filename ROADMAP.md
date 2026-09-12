# FrostByte public roadmap

**Updated September 12, 2026.** This page describes product direction, not a release schedule. The [download page](https://blackfrostai.com/frostbyte#get-beta) is the source for available builds. Planned work can change as beta feedback reveals what matters most.

## Available in the documented beta

| Area | Current behavior |
| --- | --- |
| Download sources | Selective Hugging Face downloads, torrent files, and magnet links with a review step. |
| Transfers and inventory | Grouped model progress, top-bar download search, retained completed inventory, and separate My Models/Torrents views. |
| Devices | Multiple saved Mac and DGX companions, per-device controls, hardware cards, and one destination per download. |
| Sharing | Item-level sharing controls and eligible HF + device downloads using verified files on one selected companion. |
| Updates and feedback | Manual/optional update checks, reviewed feedback, and separate optional connection diagnostics. |

The [user guide](https://blackfrostai.com/frostbyte/guide) describes prerequisites and limits. Current availability does not imply compatibility with every machine or network configuration.

## Current focus

- Reliability of transfers, pause/resume, reconnection, and inventory across devices.
- Clearer file selection, progress, error messages, and storage choices.
- Accessibility, keyboard use, and layout on supported desktop platforms.
- Useful public bug reports and actionable release follow-up.

Use the [issue tracker](https://github.com/Blackfrost-AI/FrostByte-App/issues) for specific work and its current status. A `status:planned` label identifies selected work; it does not promise a date.

## Next direction: a community directory for open models

The first step is a community of people reliably hosting and sharing files on their own machines. A later website directory could make legally redistributed open models easier to discover.

That direction includes:

- Explicit, user-initiated publishing of a listing, separate from an item's Sharing switch.
- Upstream provenance, pinned revisions, content hashes, format/quantization, size, license information, and required attribution.
- Reviewed submissions and filters that help people choose compatible files.
- Honest availability information, with reporting, correction, and removal tools.

**A public model/torrent index is not implemented in the current beta.** This feedback repository is not a listing service or a place to upload model files. Local inventory, device connections, and private/gated repositories should not silently become public listings.

Share workflows and design ideas through a [feature request](https://github.com/Blackfrost-AI/FrostByte-App/issues/new?template=02-feature-request.yml). Decisions about multi-device hybrid pooling, additional platform targets, and other capabilities will be made separately; they are not implied by the directory idea.
