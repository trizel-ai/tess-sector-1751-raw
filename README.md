# tess-sector-1751-raw

**Layer**: 1 — RAW observation source  
**Mission**: TESS (Transiting Exoplanet Survey Satellite)  
**Sector**: 1751  
**Observation window**: 2026-01-15 → 2026-01-22  
**Authority**: NASA MAST  

## Status

`download_status`: **RETRIEVAL_BLOCKED_DNS_FIREWALL**  
`upstream_status`: **PUBLISHED_AT_MAST**

Retrieval was attempted on 2026-02-20. DNS resolution for `archive.stsci.edu`, `mast.stsci.edu`, and `heasarc.gsfc.nasa.gov` failed due to environment-level network controls. This does **not** imply non-publication — independent evidence confirms Sector 1751 FFIs are published at MAST (see below).

## Upstream Publication Evidence (MAST)

| Product | DOI | Bulk Download Script |
|---------|-----|----------------------|
| Raw FFIs | `10.17909/x4aj-7547` | [`tesscurl_sector_1751_ffir.sh`](https://archive.stsci.edu/missions/tess/download_scripts/sector/tesscurl_sector_1751_ffir.sh) |
| Calibrated FFIs | `10.17909/mrs3-bw92` | [`tesscurl_sector_1751_ffic.sh`](https://archive.stsci.edu/missions/tess/download_scripts/sector/tesscurl_sector_1751_ffic.sh) |

- Archived SPOC-processed FFI frame count: **1835**
- MAST bulk downloads page: <https://archive.stsci.edu/tess/bulk_downloads/bulk_downloads_ffi-tp-lc-dv.html>

Note: TPF, LC, and DV files were expected by mid-February 2026; their current availability requires a live MAST query from a network-permitted environment.

## Contents

| Path | Description |
|------|-------------|
| `observation.meta.json` | Observation metadata (sector, cadence, coverage) |
| `provenance.json` | Data lineage and authority record |
| `integrity.sha256` | SHA-256 integrity manifest |
| `raw/tess/sector-1751/2026-01-15_2026-01-22/` | Layer-1 RAW ingest directory |
| `raw/tess/sector-1751/2026-01-15_2026-01-22/MAST_QUERY_SNAPSHOT.json` | Frozen MAST query parameters and upstream publication evidence |

## Constraints

- Layer-1 RAW only. No Layer-2 changes.
- No plots, analysis, or interpretation.
- No Gate-6 content.
- Source: NASA MAST only.
