# Contributing to FrostByte

You can help by reporting a problem, describing an improvement, answering a setup question, or making these public docs clearer. You do not need access to FrostByte's private application source.

## Choose the right route

Use the [issue chooser](https://github.com/Blackfrost-AI/FrostByte-App/issues/new/choose) for a bug, feature request, documentation correction, or question. Search [existing issues](https://github.com/Blackfrost-AI/FrostByte-App/issues?q=is%3Aissue) first, including closed reports. If you find the same problem, add your version and any new evidence there; a 👍 reaction is enough to show that a feature would help you.

Use [SECURITY.md](SECURITY.md) for vulnerabilities. Personal support details belong in a private channel described in [SUPPORT.md](SUPPORT.md). Never send credentials.

## Write a clear bug report

A useful title names the action and the failure. For example:

- “Transfers stops updating after a companion reconnects”
- “Selected files are clipped at the minimum window size on Windows”
- “Completed model is missing from inventory after clearing history”

State your app version and desktop platform. Describe the steps, actual behavior, expected behavior, and whether the problem repeats. For remote problems, identify the companion platform and whether storage is internal or external. Model family, file format, approximate size, and shard count are usually more useful than personal paths or a full system report.

If you cannot reproduce it reliably, explain what was happening when you noticed it. Do not delete files, reset your app profile, change system protections, or repeat a large download just to produce a report. Describe any workaround you have already tried and whether it changed the result.

Attachments are optional. Crop or redact screenshots and share only the short log excerpt needed to explain the issue. Remove account names, tokens, keys, invite codes, network addresses, file paths, and unrelated download history. Avoid full settings/profile exports or environment dumps.

## Propose an improvement

Start with the problem and the workflow. Explain who it affects, what is difficult today, and what result would help. A possible UI or implementation idea is welcome, but it is not required. Include accessibility needs or compatibility requirements when relevant.

A request to support a new device should describe its platform, model family, and the intended workflow. Do not post a serial number, SSH address, password, or private key. Roadmap discussion is welcome; dates and implementation decisions come from maintainers after review.

## Improve these docs

Small documentation pull requests are welcome. Keep the change focused, explain which reader it helps, and check links and Markdown formatting. The pull request template provides a place to summarize that review.

This repository contains community documentation and issue forms. Application fixes are tracked through issues and implemented in the separate development workflow. Keep application source, binaries, model files, private screenshots, credentials, and build artifacts out of documentation contributions. Discuss large restructures or new automation in an issue before submitting them.

## How triage works

1. A report starts with `status:triage` and a type label from its form.
2. Maintainers review the scope, look for duplicates, and add relevant platform or area labels.
3. `status:needs-info` identifies a specific question that would help investigation. Maintainers use `status:confirmed` once a bug is verified.
4. Selected work can move to `status:planned` and then `status:in-progress`.
5. Use `status:released` only when the closing or follow-up comment identifies the build containing the change. Implementation completion alone is not a release.

Keep one active status label where practical. Priority reflects user impact and maintainer assessment, not the number of reminders. If closing a report as a duplicate, link its replacement; if it is outside scope, explain why. Public updates should summarize behavior and release versions without exposing private development material.

The label definitions are in [.github/labels.json](.github/labels.json). Area labels are applied during triage; selecting an area in a form does not automatically change labels.

Everyone participating is expected to follow the [community guidelines](CODE_OF_CONDUCT.md). We welcome detailed criticism of the product and constructive disagreement about how it should work.
