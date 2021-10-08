<!--
SPDX-FileCopyrightText: 2021 Andre 'Staltz' Medeiros

SPDX-License-Identifier: CC-BY-4.0
-->

## Slack URIs

https://api.slack.com/reference/deep-linking

### Summary

- URIs with an *authority* component (`slack://`)
- *Authority* specifies either actions (e.g. "share-file") or content (e.g. "channel")
- Any other identifiers are put in the *query* component

### Examples

- `slack://open`
- `slack://open?team={TEAM_ID}`
- `slack://app?team={TEAM_ID}&id={APP_ID}`
- `slack://app?team={TEAM_ID}&id={APP_ID}&tab=home`
- `slack://channel?team={TEAM_ID}&id={CHANNEL_ID}`
- `slack://user?team={TEAM_ID}&id={USER_ID}`
- `slack://file?team={TEAM_ID}&id={FILE_ID}`
- `slack://share-file?team={TEAM_ID}&id={FILE_ID}`