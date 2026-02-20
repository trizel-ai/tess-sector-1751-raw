# TESS Sector-1751 — Layer-1 RAW Ingest Snapshot (2026-01-15 → 2026-01-22)

**Layer**: 1 — RAW ingest snapshot only.  
**RAW files in custody**: NOT PRESENT — retrieval was blocked by environment-level DNS/firewall controls.  
**Upstream publication status**: PUBLISHED AT MAST (see DOIs below).  
**No interpretation. No results.**

## Authority

All data originates from **NASA MAST** (Mikulski Archive for Space Telescopes):  
<https://mast.stsci.edu/>

Official TESS archive: <https://archive.stsci.edu/tess/>

## Contents

| File | Description |
|------|-------------|
| `MAST_QUERY_SNAPSHOT.json` | Frozen MAST query template, parameters, and upstream publication evidence for the Jan 15–22 2026 observation window |

## Upstream Publication Evidence (MAST)

The following products for Sector 1751 are confirmed published at NASA MAST via DOI registration and bulk-download listing:

| Product | DOI | Bulk Download Script |
|---------|-----|----------------------|
| Raw FFIs | `10.17909/x4aj-7547` | `tesscurl_sector_1751_ffir.sh` |
| Calibrated FFIs | `10.17909/mrs3-bw92` | `tesscurl_sector_1751_ffic.sh` |

- Archived SPOC-processed FFI frame count: **1835**
- MAST bulk downloads page: <https://archive.stsci.edu/tess/bulk_downloads/bulk_downloads_ffi-tp-lc-dv.html>
- MAST access article (Jan 29, 2026): <https://archive.stsci.edu/contents/newsletters/january-2026/tess-3i-atlas>

Note: TPF, LC, and DV files from Sector 1751 were expected in mid-February 2026; their current availability requires a live MAST query from a network-permitted environment.

## Integrity

SHA-256 checksums are maintained in the root `integrity.sha256` manifest. The current manifest covers only the snapshot metadata files.

## Status

`download_status`: **RETRIEVAL_BLOCKED_DNS_FIREWALL**  
`upstream_publication`: **CONFIRMED AT MAST**

Upstream FFIs are published at MAST (see DOIs). This environment could not retrieve them due to DNS/firewall restrictions. No ingestion is claimed.
