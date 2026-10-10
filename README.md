# GHCN-Daily station file captures

Byte-identical copies of 198 NOAA GHCN-Daily station files and the GHCN-Daily readme, as archived by the Internet Archive's Wayback Machine.

The files are in this repository's release `v1`. They are kept here because individual Wayback captures sometimes stop playing back (a capture can start redirecting to another date), which breaks builds that fetch them by URL.

- Every file is unchanged from its Wayback capture. `PROVENANCE.csv` gives, for each file, the station, the original NOAA URL, the Wayback timestamp and `id_` URL, the CDX SHA-1 digest, the SHA-256 and the size.
- `SHA256SUMS` lists the SHA-256 of every file. Check with `sha256sum -c SHA256SUMS`.
- The data is published by NOAA's National Centers for Environmental Information and is in the public domain (U.S. Government work).

Source: https://www.ncei.noaa.gov/pub/data/ghcn/daily/
