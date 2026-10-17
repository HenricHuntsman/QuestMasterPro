# Archive inventory

Updated 18 October 2026. This repository preserves historical QuestMaster/Azeroth snapshots; the maintained addon is [QuestMaster-Pro](https://github.com/HenricHuntsman/QuestMaster-Pro).

## Retained addon snapshots

| File | Current verification | Decision |
| --- | --- | --- |
| azeroth-pilot-reloaded-Pro--main (1).zip | Readable ZIP, 61 entries, CRC check passed; SHA-256 `91c688f4caa8710f495306734895e1de6111baa2b5cb0d2b0531e7b119b15ce5` | Keep pending comparison with maintained source |
| azeroth-pilot-reloaded-feature-complete-rewrite-experimental.zip | The earlier July inventory described 270 entries and unique experimental areas. The current file read did not return its payload, so that description was not reverified today | Preserve; do not discard or merge unreviewed code |

A readable ZIP and CRC check establish archive integrity, not addon correctness, licence compliance, or compatibility.

## Misfiled Book Publish Forge duplicate removed

The former `files (2).zip` was unrelated Book Publish Forge React prototype material. Both repository copies were read and independently inspected on 18 October:

- 86 entries; CRC checks passed.
- 175,528 bytes per archive.
- Identical Git blob SHA: `8915cf7b1ad5a6c2aa514efce72893f1f3355ba5`.
- Identical SHA-256: `b64acb87fa90ee0bde09034f3ccf18c30ebda19e11c90af98a7266d895f80da1`.

The redundant copy was removed from this repository as part of Henric's requested cleanup. The original remains in [Book Publish Forge](https://github.com/HenricHuntsman/book-publish-forge/blob/main/files%20(2).zip), and this repository's Git history retains the removed blob.

The prototype includes writing, AI, collaboration, dashboard and export components. Its contents were listed and CRC-checked, not security-reviewed or promoted into the active app.

## Remaining work

Compare the two retained addon archives against current source, review unique code and provenance, and run addon-specific checks before recovering features. Repository renaming, whole-repository archival and deletion have not been performed.
