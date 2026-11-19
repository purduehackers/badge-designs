# Badge designs

Hack Night and Hack Lite badge and stamp artwork, linked to Purdue Hackers CMS events.

102 events · 60 badge/stamp pairs · 193 SVG files.

## Files

Each event lives in `badges/<version>/`. Hack Lite uses `hack-lite-spring-<year>`.

- `badge.svg` and `stamp.svg` contain the individual artwork when recovered.
- `badge-back.svg` preserves a second badge face when applicable.
- `*-preview.png` files show the artwork against gray; that background is not in the SVG.
- `variants/` contains alternatives whose final selection is unconfirmed. `cutting-sheet.svg` is a repeated manufacturing layout, not an individual badge.
- `metadata.json` contains only CMS, author, and reviewer references.

Historical artwork is preserved with its existing colors, geometry, and printed labels. Importing a file does not certify it for manufacturing. Missing files stay absent; unknown author or reviewer fields stay null.

```json
{
  "cms": { "id": "<id>", "slug": "<slug>" },
  "author": { "id": null, "username": null },
  "reviewer": { "id": null, "username": null }
}
```

IDs are strings. The folder identifies the version; the CMS supplies the date. Reviewer means a human final approver, not the uploader or the person importing the files.

## Catalog

| Event                                                  | Badge                                         | Stamp                                         |
| ------------------------------------------------------ | --------------------------------------------- | --------------------------------------------- |
| [1.0](badges/1.0/)                                     | [SVG](badges/1.0/badge.svg)                   | Not identified                                |
| [1.1](badges/1.1/)                                     | [SVG](badges/1.1/badge.svg)                   | Not identified                                |
| [1.2](badges/1.2/)                                     | [SVG](badges/1.2/badge.svg)                   | Not identified                                |
| [1.3](badges/1.3/)                                     | [SVG](badges/1.3/badge.svg)                   | Not identified                                |
| [1.4](badges/1.4/)                                     | [SVG](badges/1.4/badge.svg)                   | Not identified                                |
| [1.5](badges/1.5/)                                     | Variants only                                 | Not identified                                |
| [2.0](badges/2.0/)                                     | [SVG](badges/2.0/badge.svg)                   | Not identified                                |
| [2.1](badges/2.1/)                                     | Variants only                                 | Not identified                                |
| [2.2](badges/2.2/)                                     | [SVG](badges/2.2/badge.svg)                   | Not identified                                |
| [2.3](badges/2.3/)                                     | [SVG](badges/2.3/badge.svg)                   | Not identified                                |
| [2.4](badges/2.4/)                                     | Variants only                                 | Not identified                                |
| [2.5](badges/2.5/)                                     | [SVG](badges/2.5/badge.svg)                   | Not identified                                |
| [2.6](badges/2.6/)                                     | [SVG](badges/2.6/badge.svg)                   | Not identified                                |
| [2.7](badges/2.7/)                                     | [SVG](badges/2.7/badge.svg)                   | Not identified                                |
| [3.0-beta](badges/3.0-beta/)                           | [SVG](badges/3.0-beta/badge.svg)              | Not identified                                |
| [3.0](badges/3.0/)                                     | [SVG](badges/3.0/badge.svg)                   | Not identified                                |
| [3.1](badges/3.1/)                                     | [SVG](badges/3.1/badge.svg)                   | Not identified                                |
| [3.2](badges/3.2/)                                     | Layout only                                   | Not identified                                |
| [3.3](badges/3.3/)                                     | [SVG](badges/3.3/badge.svg)                   | Not identified                                |
| [3.4](badges/3.4/)                                     | [SVG](badges/3.4/badge.svg)                   | Not identified                                |
| [3.5](badges/3.5/)                                     | [SVG](badges/3.5/badge.svg)                   | Not identified                                |
| [3.6](badges/3.6/)                                     | Variants only                                 | Not identified                                |
| [3.7](badges/3.7/)                                     | Variants only                                 | Not identified                                |
| [3.8](badges/3.8/)                                     | [SVG](badges/3.8/badge.svg)                   | Not identified                                |
| [3.9](badges/3.9/)                                     | [SVG](badges/3.9/badge.svg)                   | Not identified                                |
| [3.10](badges/3.10/)                                   | [SVG](badges/3.10/badge.svg)                  | Not identified                                |
| [3.11](badges/3.11/)                                   | Variants only                                 | Not identified                                |
| [3.12](badges/3.12/)                                   | [SVG](badges/3.12/badge.svg)                  | Not identified                                |
| [3.13](badges/3.13/)                                   | [SVG](badges/3.13/badge.svg)                  | Not identified                                |
| [3.15](badges/3.15/)                                   | [SVG](badges/3.15/badge.svg)                  | Not identified                                |
| [4.0](badges/4.0/)                                     | [SVG](badges/4.0/badge.svg)                   | [SVG](badges/4.0/stamp.svg)                   |
| [4.1](badges/4.1/)                                     | [SVG](badges/4.1/badge.svg)                   | [SVG](badges/4.1/stamp.svg)                   |
| [4.2](badges/4.2/)                                     | [SVG](badges/4.2/badge.svg)                   | [SVG](badges/4.2/stamp.svg)                   |
| [4.3](badges/4.3/)                                     | Variants only                                 | [SVG](badges/4.3/stamp.svg)                   |
| [4.4](badges/4.4/)                                     | Variants only                                 | [SVG](badges/4.4/stamp.svg)                   |
| [4.5](badges/4.5/)                                     | Variants only                                 | [SVG](badges/4.5/stamp.svg)                   |
| [4.6](badges/4.6/)                                     | [SVG](badges/4.6/badge.svg)                   | [SVG](badges/4.6/stamp.svg)                   |
| [4.7](badges/4.7/)                                     | [SVG](badges/4.7/badge.svg)                   | [SVG](badges/4.7/stamp.svg)                   |
| [4.7.1](badges/4.7.1/)                                 | [SVG](badges/4.7.1/badge.svg)                 | [SVG](badges/4.7.1/stamp.svg)                 |
| [5.0](badges/5.0/)                                     | [SVG](badges/5.0/badge.svg)                   | [SVG](badges/5.0/stamp.svg)                   |
| [5.1](badges/5.1/)                                     | [SVG](badges/5.1/badge.svg)                   | [SVG](badges/5.1/stamp.svg)                   |
| [5.2](badges/5.2/)                                     | [SVG](badges/5.2/badge.svg)                   | [SVG](badges/5.2/stamp.svg)                   |
| [5.3](badges/5.3/)                                     | Variants only                                 | [SVG](badges/5.3/stamp.svg)                   |
| [5.4](badges/5.4/)                                     | [SVG](badges/5.4/badge.svg)                   | [SVG](badges/5.4/stamp.svg)                   |
| [5.5](badges/5.5/)                                     | [SVG](badges/5.5/badge.svg)                   | [SVG](badges/5.5/stamp.svg)                   |
| [5.6](badges/5.6/)                                     | [SVG](badges/5.6/badge.svg)                   | [SVG](badges/5.6/stamp.svg)                   |
| [5.7](badges/5.7/)                                     | [SVG](badges/5.7/badge.svg)                   | [SVG](badges/5.7/stamp.svg)                   |
| [5.8](badges/5.8/)                                     | Layout only                                   | [SVG](badges/5.8/stamp.svg)                   |
| [5.9](badges/5.9/)                                     | Role unconfirmed                              | Not identified                                |
| [5.10](badges/5.10/)                                   | [SVG](badges/5.10/badge.svg)                  | [SVG](badges/5.10/stamp.svg)                  |
| [5.11](badges/5.11/)                                   | [SVG](badges/5.11/badge.svg)                  | [SVG](badges/5.11/stamp.svg)                  |
| [5.12](badges/5.12/)                                   | [SVG](badges/5.12/badge.svg)                  | [SVG](badges/5.12/stamp.svg)                  |
| [5.13](badges/5.13/)                                   | [SVG](badges/5.13/badge.svg)                  | [SVG](badges/5.13/stamp.svg)                  |
| [5.14](badges/5.14/)                                   | Layout only                                   | [SVG](badges/5.14/stamp.svg)                  |
| [5.15](badges/5.15/)                                   | Variants only                                 | [SVG](badges/5.15/stamp.svg)                  |
| [5.16](badges/5.16/)                                   | [SVG](badges/5.16/badge.svg)                  | [SVG](badges/5.16/stamp.svg)                  |
| [5.17](badges/5.17/)                                   | [SVG](badges/5.17/badge.svg)                  | [SVG](badges/5.17/stamp.svg)                  |
| [5.18](badges/5.18/)                                   | [SVG](badges/5.18/badge.svg)                  | [SVG](badges/5.18/stamp.svg)                  |
| [5.19](badges/5.19/)                                   | [SVG](badges/5.19/badge.svg)                  | [SVG](badges/5.19/stamp.svg)                  |
| [5.20](badges/5.20/)                                   | [SVG](badges/5.20/badge.svg)                  | [SVG](badges/5.20/stamp.svg)                  |
| [5.21](badges/5.21/)                                   | [SVG](badges/5.21/badge.svg)                  | [SVG](badges/5.21/stamp.svg)                  |
| [5.22](badges/5.22/)                                   | [SVG](badges/5.22/badge.svg)                  | [SVG](badges/5.22/stamp.svg)                  |
| [5.23](badges/5.23/)                                   | [SVG](badges/5.23/badge.svg)                  | [SVG](badges/5.23/stamp.svg)                  |
| [5.24](badges/5.24/)                                   | [SVG](badges/5.24/badge.svg)                  | [SVG](badges/5.24/stamp.svg)                  |
| [5.25](badges/5.25/)                                   | [SVG](badges/5.25/badge.svg)                  | [SVG](badges/5.25/stamp.svg)                  |
| [5.25.1](badges/5.25.1/)                               | [SVG](badges/5.25.1/badge.svg)                | [SVG](badges/5.25.1/stamp.svg)                |
| [6.0](badges/6.0/)                                     | [SVG](badges/6.0/badge.svg)                   | [SVG](badges/6.0/stamp.svg)                   |
| [6.1](badges/6.1/)                                     | [SVG](badges/6.1/badge.svg)                   | [SVG](badges/6.1/stamp.svg)                   |
| [6.2](badges/6.2/)                                     | [SVG](badges/6.2/badge.svg)                   | [SVG](badges/6.2/stamp.svg)                   |
| [6.3](badges/6.3/)                                     | [SVG](badges/6.3/badge.svg)                   | [SVG](badges/6.3/stamp.svg)                   |
| [6.4](badges/6.4/)                                     | [SVG](badges/6.4/badge.svg)                   | Not identified                                |
| [6.5](badges/6.5/)                                     | [SVG](badges/6.5/badge.svg)                   | [SVG](badges/6.5/stamp.svg)                   |
| [6.6](badges/6.6/)                                     | Layout only                                   | [SVG](badges/6.6/stamp.svg)                   |
| [6.7](badges/6.7/)                                     | [SVG](badges/6.7/badge.svg)                   | [SVG](badges/6.7/stamp.svg)                   |
| [6.8](badges/6.8/)                                     | [SVG](badges/6.8/badge.svg)                   | [SVG](badges/6.8/stamp.svg)                   |
| [6.9](badges/6.9/)                                     | [SVG](badges/6.9/badge.svg)                   | [SVG](badges/6.9/stamp.svg)                   |
| [6.10](badges/6.10/)                                   | [SVG](badges/6.10/badge.svg)                  | [SVG](badges/6.10/stamp.svg)                  |
| [6.12](badges/6.12/)                                   | [SVG](badges/6.12/badge.svg)                  | [SVG](badges/6.12/stamp.svg)                  |
| [6.13](badges/6.13/)                                   | [SVG](badges/6.13/badge.svg)                  | [SVG](badges/6.13/stamp.svg)                  |
| [6.14](badges/6.14/)                                   | [SVG](badges/6.14/badge.svg)                  | [SVG](badges/6.14/stamp.svg)                  |
| [6.15](badges/6.15/)                                   | [SVG](badges/6.15/badge.svg)                  | [SVG](badges/6.15/stamp.svg)                  |
| [6.16](badges/6.16/)                                   | Variants only                                 | [SVG](badges/6.16/stamp.svg)                  |
| [6.17](badges/6.17/)                                   | [SVG](badges/6.17/badge.svg)                  | [SVG](badges/6.17/stamp.svg)                  |
| [6.18](badges/6.18/)                                   | [SVG](badges/6.18/badge.svg)                  | [SVG](badges/6.18/stamp.svg)                  |
| [6.19](badges/6.19/)                                   | [SVG](badges/6.19/badge.svg)                  | [SVG](badges/6.19/stamp.svg)                  |
| [6.20](badges/6.20/)                                   | [SVG](badges/6.20/badge.svg)                  | [SVG](badges/6.20/stamp.svg)                  |
| [6.21](badges/6.21/)                                   | [SVG](badges/6.21/badge.svg)                  | [SVG](badges/6.21/stamp.svg)                  |
| [6.22](badges/6.22/)                                   | [SVG](badges/6.22/badge.svg)                  | [SVG](badges/6.22/stamp.svg)                  |
| [6.23](badges/6.23/)                                   | [SVG](badges/6.23/badge.svg)                  | [SVG](badges/6.23/stamp.svg)                  |
| [6.24](badges/6.24/)                                   | [SVG](badges/6.24/badge.svg)                  | [SVG](badges/6.24/stamp.svg)                  |
| [6.25](badges/6.25/)                                   | [SVG](badges/6.25/badge.svg)                  | [SVG](badges/6.25/stamp.svg)                  |
| [6.26](badges/6.26/)                                   | [SVG](badges/6.26/badge.svg)                  | [SVG](badges/6.26/stamp.svg)                  |
| [6.26.1](badges/6.26.1/)                               | [SVG](badges/6.26.1/badge.svg)                | [SVG](badges/6.26.1/stamp.svg)                |
| [7.0](badges/7.0/)                                     | [SVG](badges/7.0/badge.svg)                   | [SVG](badges/7.0/stamp.svg)                   |
| [7.1](badges/7.1/)                                     | [SVG](badges/7.1/badge.svg)                   | [SVG](badges/7.1/stamp.svg)                   |
| [7.2](badges/7.2/)                                     | [SVG](badges/7.2/badge.svg)                   | [SVG](badges/7.2/stamp.svg)                   |
| [7.3](badges/7.3/)                                     | [SVG](badges/7.3/badge.svg)                   | [SVG](badges/7.3/stamp.svg)                   |
| [7.4](badges/7.4/)                                     | [SVG](badges/7.4/badge.svg)                   | [SVG](badges/7.4/stamp.svg)                   |
| [hack-lite-spring-2023](badges/hack-lite-spring-2023/) | Layout only                                   | Not identified                                |
| [hack-lite-spring-2024](badges/hack-lite-spring-2024/) | [SVG](badges/hack-lite-spring-2024/badge.svg) | [SVG](badges/hack-lite-spring-2024/stamp.svg) |
| [hack-lite-spring-2025](badges/hack-lite-spring-2025/) | [SVG](badges/hack-lite-spring-2025/badge.svg) | [SVG](badges/hack-lite-spring-2025/stamp.svg) |
| [hack-lite-spring-2026](badges/hack-lite-spring-2026/) | [SVG](badges/hack-lite-spring-2026/badge.svg) | [SVG](badges/hack-lite-spring-2026/stamp.svg) |

## Artwork not recovered

These past CMS events have no matching artwork in this import. Their absence does not establish whether a physical badge existed.

| CMS event                 | ID  | Slug             |
| ------------------------- | --- | ---------------- |
| Hack Night 0.1            | 129 | `0.1`            |
| Hack Night 0.2            | 102 | `0.2`            |
| Hack Night 0.3            | 72  | `0.3`            |
| Hack Night 0.4            | 75  | `0.4`            |
| Hack Night 0.5            | 119 | `0.5`            |
| Hack Night 0.6            | 144 | `0.6`            |
| Hack Night: Encore        | 123 | `encore`         |
| Hack Night 3.11.1         | 62  | `3.11.1`         |
| Hack Night 3.14           | 106 | `3.14`           |
| Hack Night 3.16           | 78  | `3.16`           |
| Hack Night Snapshot 24w20 | 139 | `snapshot-24w20` |
| Hack Night 6.11           | 157 | `6.11`           |
| Hack Night 6.11.1         | 158 | `6.11.1`         |

## Revisions

Submit corrections through a pull request in the same event directory, update affected previews, and retain the CMS identity. Git records revision history. Do not invent missing attribution or approval.
