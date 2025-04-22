### Peer-host resolution

Spacetele supports peer resolution, allowing to map mnemonic names (.ie myserver) with a peer public key. Search priority is `.`, `~/`, `/etc/` `/Users`.

```
example: ~/.space-hosts

myserver PEER_KEY_0
workserver PEER_KEY_1
```
