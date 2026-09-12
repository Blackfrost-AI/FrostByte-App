# Support

Start with the [illustrated user guide](https://blackfrostai.com/frostbyte/guide). The [official download page](https://blackfrostai.com/frostbyte#get-beta) identifies the current build and installation requirements.

## Public and private feedback

| Situation | Recommended channel |
| --- | --- |
| A reproducible bug or a feature idea that can be discussed publicly | [Open an issue](https://github.com/Blackfrost-AI/FrostByte-Feedback/issues/new/choose) |
| General setup or usage question | [Question form](https://github.com/Blackfrost-AI/FrostByte-Feedback/issues/new?template=04-question.yml) |
| A private report or a report without a GitHub account | In the app, use **Help → Send feedback** or **Settings → Privacy & Feedback**; review before sending |
| Trouble getting access to the invited beta | Email [support@blackfrostai.com](mailto:support@blackfrostai.com) without your invite code or credentials |
| A suspected vulnerability or sensitive security concern | Follow [SECURITY.md](SECURITY.md) and use GitHub's private reporting route |

In-app feedback is sent to Blackfrost's private feedback service and is not automatically posted to this repository. A reply email and diagnostics attachment are optional. Public issues are readable by anyone and may be indexed by search engines. A GitHub account is needed to post an issue; reading the documentation and public reports does not require one.

## Quick troubleshooting

### I cannot find a completed download

Use the top bar or **Cmd/Ctrl+F**, enter part of a recorded model/file name or folder, and press Enter. In Transfers, choose **All devices** if you are unsure where the download went. Also check **My Models** and **Torrents**; an item's category can be changed through its options.

Clearing finished transfer history keeps downloaded inventory. Offline devices show last known information until they reconnect. Inventory covers files recorded by FrostByte; it is not a full search of every file on every disk. Report a missing item with your app version, local/remote context, and the action that preceded it. You do not need to publish its name or path.

### Hugging Face search or access fails

Use the **HuggingFace** tab for online model search. The top bar searches your downloads. Clear restrictive Hub filters and check whether the public model page is reachable in your browser. A gated or private repository may need publisher approval and a token for an account that already has access. Manage the token in **Settings → HuggingFace**; never paste it into an issue.

Report the visible error and whether public browsing or only restricted access is affected. Optional details such as format and selected-file count can help; a private repository URL is not required.

### A magnet is waiting for peers or has no file list

Magnet metadata comes from reachable peers. A link can be valid while its sources are offline. Compare with a small torrent you are authorized to download and that has a known available source. Note whether the issue affects one source or every torrent. Do not change firewall/security settings or publish the magnet just to file a report.

### A device or external drive is unavailable

Confirm that the remote computer is awake and reachable from your normal environment. A Mac companion needs its account logged in. Check that an external drive is mounted and that the selected folder still exists. Reconnect through **Devices** and inspect the displayed connection message.

A missing selected destination blocks a new download; it should not silently redirect to another disk. One download uses one selected device and folder. Browsing elsewhere does not change that choice. Report the companion platform and storage type, with private addresses and paths removed.

### An installer is blocked

Check the release's signing status and official installation instructions on the [download page](https://blackfrostai.com/frostbyte#get-beta). The documented beta is not notarized on Mac and is unsigned on Windows. Report the exact system message and OS version, or use private support. Keep system protections enabled.

### I want to check for updates

Open **Settings → Updates → Check now**. Automatic checking is optional and runs at most daily while the app is open. A check only reads release information; the invite-protected website supplies downloads, and you choose when to install.

## What support needs

Usually: app version, OS version, the affected feature, a short description of the action and result, and local versus companion context. Optional screenshots should show only the relevant area. Never send passwords, tokens, SSH private keys, invite codes, full profile exports, or unrelated download history, even through private support.

Do not post a separate issue repeatedly to seek a faster response. Add useful new information to the existing report. There is no guaranteed response time or delivery date during the private beta.
