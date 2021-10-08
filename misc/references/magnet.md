<!--
SPDX-FileCopyrightText: 2021 Andre 'Staltz' Medeiros

SPDX-License-Identifier: CC-BY-4.0
-->

## Magnet URIs

http://magnet-uri.sourceforge.net/magnet-draft-overview.txt

### Summary

- All information is put in the *query* component
- Identifiers are specified as *URNs* embedded in the query component

### Examples

- `magnet:?xt=urn:btih:c12fe1c06bba254a9dc9f519b335aa7c1367a88a`
- `magnet:?xt=urn:btmh:<tagged-info-hash>&dn=<name>&tr=<tracker-url>`
- `magnet:?xt=urn:btmh:1220caf1e1c30e81cb361b9ee167c4aa64228a7fa4fa9f6105232b28ad099f3a302e&dn=bittorrent-v2-test`
- `magnet:?xt=urn:btih:631a31dd0a46257d5078c0dee4e66e26f73e42ac&xt=urn:btmh:1220d8dd32ac93357c368556af3ac1d95c9d76bd0dff6fa9833ecdac3d53134efabb&dn=bittorrent-v1-v2-hybrid-test`