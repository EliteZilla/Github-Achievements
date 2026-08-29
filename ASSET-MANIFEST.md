# Asset Manifest

This file defines the final self-hosted filenames for the GitHub badge archive.

The initial README deliberately uses official GitHub-hosted artwork where a direct current asset was verified, plus archival image references for historical/test/internal artwork. The final repository should copy each verified original into the matching local path and then replace the remote image URL in README.md.

## Current / Retired Achievement Defaults

| Achievement | Local destination | Verified current artwork source |
|---|---|---|
| Pair Extraordinaire | `assets/achievements/pair-extraordinaire/default.png` | `https://github.githubassets.com/assets/pair-extraordinaire-default-579438a20e01.png` |
| Quickdraw | `assets/achievements/quickdraw/default.png` | `https://github.githubassets.com/assets/quickdraw-default-39c6aec8ff89.png` |
| Starstruck | `assets/achievements/starstruck/default.png` | `https://github.githubassets.com/assets/starstruck-default-b6610abad518.png` |
| Galaxy Brain | `assets/achievements/galaxy-brain/default.png` | `https://github.githubassets.com/assets/galaxy-brain-default-847262c21056.png` |
| Pull Shark | `assets/achievements/pull-shark/default.png` | `https://github.githubassets.com/assets/pull-shark-default-498c279a747d.png` |
| YOLO | `assets/achievements/yolo/default.png` | `https://github.githubassets.com/assets/yolo-default-be0bbff04951.png` |
| Public Sponsor | `assets/achievements/public-sponsor/default.png` | `https://github.githubassets.com/assets/public-sponsor-default-9fa68986b057.png` |
| Arctic Code Vault Contributor | `assets/retired/arctic-code-vault-contributor/default.png` | `https://github.githubassets.com/assets/arctic-code-vault-contributor-default-df8d74122a06.png` |
| Mars 2020 Contributor | `assets/retired/mars-2020-contributor/default.png` | `https://github.githubassets.com/assets/mars-2020-contributor-default-c9cad8495acf.png` |

## Tier Files

### Pair Extraordinaire
- `assets/achievements/pair-extraordinaire/bronze-x2.png`
- `assets/achievements/pair-extraordinaire/silver-x3.png`
- `assets/achievements/pair-extraordinaire/gold-x4.png`

### Starstruck
- `assets/achievements/starstruck/bronze-x2.png`
- `assets/achievements/starstruck/silver-x3.png`
- `assets/achievements/starstruck/gold-x4.png`

### Galaxy Brain
- `assets/achievements/galaxy-brain/bronze-x2.png`
- `assets/achievements/galaxy-brain/silver-x3.png`
- `assets/achievements/galaxy-brain/gold-x4.png`

### Pull Shark
- `assets/achievements/pull-shark/bronze-x2.png`
- `assets/achievements/pull-shark/silver-x3.png`
- `assets/achievements/pull-shark/gold-x4.png`

### Heart On Your Sleeve (disabled/test)
- `assets/experimental/heart-on-your-sleeve/default.png`
- `assets/experimental/heart-on-your-sleeve/bronze-x2.png`
- `assets/experimental/heart-on-your-sleeve/silver-x3.png`
- `assets/experimental/heart-on-your-sleeve/gold-x4.png`

### Open Sourcerer (disabled/test)
- `assets/experimental/open-sourcerer/default.png`
- `assets/experimental/open-sourcerer/bronze-x2.png`
- `assets/experimental/open-sourcerer/silver-x3.png`
- `assets/experimental/open-sourcerer/gold-x4.png`

## Internal Achievement Files

- `assets/internal/proxima-pioneer/default.png`
- `assets/internal/proxima-staffshipper/default.png`
- `assets/internal/proxima-staffuser/default.png`

## Legacy 2021 Files

- `assets/legacy/achievements-2021/arctic-code-vault-contributor/default.png`
- `assets/legacy/achievements-2021/github-sponsor/default.png`
- `assets/legacy/achievements-2021/mars-2020-helicopter-contributor/default.png`

## Profile / Program Badge Files

- `assets/profile-badges/developer-program-member/default.png`
- `assets/profile-badges/pro/default.png`
- `assets/profile-badges/security-bug-bounty-hunter/default.png`
- `assets/profile-badges/github-campus-expert/default.png`
- `assets/profile-badges/security-advisory-credit/default.png`
- `assets/profile-badges/github-star/default.png`

## Other GitHub Badge Files

- `assets/organization/verified/default.png`
- `assets/marketplace/publisher-verified/default.png`
- `assets/marketplace/listing-requirements/default.png`
- `assets/legacy/profile-highlights/discussion-answered/default.png`

## Naming Rule

Use:
- `default.png`
- `bronze-x2.png`
- `silver-x3.png`
- `gold-x4.png`

Avoid hashed CDN filenames in the self-hosted repository. This keeps README paths stable if GitHub changes its CDN hashes.
