<!--
SPDX-FileCopyrightText: 2021 Andre 'Staltz' Medeiros

SPDX-License-Identifier: CC-BY-4.0
-->

## SSBs URIs with query only

### Summary

**Content** uses the `ref` query parameter:

```
ssb:?ref=<URN>
```

**Multiserver addresses** use the `msaddr` query parameter where the value `<MULTISERVERADDRESS>` a [multiserver address](https://github.com/ssbc/multiserver-address) escaped as URI-safe characters:

```
ssb:?msaddr=<MULTISERVERADDRESS>
```

### Examples

- `ssb:?ref=urn:message:sha256:g3hPVPDEO1Aj\_uPl0-J2NlhFB2bbFLIHlty-YuqFZ3w=`
- `ssb:?ref=urn:feed:ed25519:-oaWWDs8g73EZFUMfW37R\_ULtFEjwKN\_DczvdYihjbU=`
- `ssb:?ref=urn:blob:sha256:sbBmsB7XWvmIzkBzreYcuzPpLtpeCMDIs6n\_OJGSC1U=`
- `ssb:?addr=net%3A88.198.115.222%3A8008~shs%3Aim4Qn0fCzpD3YfsegHFLJzkNXYUb%2FnYnlfuCf%2BLmPuM%3D`

### Verdict

This would be nice, but `ssb-uri` is currently sufficiently well established in clients like Patchwork and Patchfoo for **content** URIs such as `ssb:message:sha256:<MSGID>`. We may not want to supercede that specification so quickly, not without community discussion.