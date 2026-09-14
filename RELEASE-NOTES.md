# FrostByte 0.3.0 — public beta

- Optional publisher identity setup now preserves its recovery backup requirement
  across restarts, clears exposed recovery text, and uses protected local key storage.
- Publisher signatures match AEON’s format. AEON Orbit includes typography and
  appearance refinements contributed through the collaboration.
- Versioned release records now verify that Mac and Windows packages come from
  the same source revision and match their published SHA-256 checksums.
- Updated first-launch notices align public access and optional publisher storage.
  Connection diagnostics remain optional and exclude download history.

[Download for Mac and Windows](https://blackfrostai.com/frostbyte#get-beta) ·
[User guide](https://blackfrostai.com/frostbyte/guide)

Existing users: Settings → Updates → Check now. Optional daily checks are available;
you decide when to download and install. The beta remains ad-hoc signed and not
notarized on Mac, and unsigned on Windows. Keep operating-system protections enabled.

The existing Hugging Face, BitTorrent, IPFS, grouped transfer, sharing and device
features carry forward. Publisher identity setup does not publish files; Frost-Net
and the combined AEON Raspberry Pi image are not included in this release.
