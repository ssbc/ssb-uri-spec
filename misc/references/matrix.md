## Matrix URIs

https://github.com/matrix-org/matrix-doc/pull/2312

### Summary

- URIs with clear definitions of the *path* component
- Covers content and addresses (users, rooms, events)
- Actions are encoded in the *query* component

### Examples

- `matrix:r/someroom:example.org`
- `matrix:r/someroom:example.org?action=join`
- `matrix:roomid/rid:example.org`
- `matrix:r/someroom:example.org/e/lol823y4bcp3qo4`
- `matrix:u/her:example.org`
- `matrix:u/her:example.org?action=chat`