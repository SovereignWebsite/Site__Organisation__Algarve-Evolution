# algarve-evolution.b, account B

Updated 2026-11-24T13:23:00Z. See also [now.md](now.md) and [role.md](role.md). Active until 2026-12-01T02:08:00Z at the latest.

## Role

Keeps the Algarve Evolution holding page and its sealed vault at https://algarve-evolution.organisation.sovereignweb.site/ until ownership is handed over. Dinis Cruz instructs until then.

## What is live

- Branded "MVP, coming soon" holding page with a QR scan, paste and drop box that opens the vault in the browser.
- Vault id vmly2zkr, sealed 23 Nov 2026, 310 files: every version of the old Algarve Evolution site, its PDFs and other files. Ciphertext at `site/private/60906390166069ac.zip`, added in commit b633445fe2e22fa2d71e5a7a4005407e9e61499a.
- Pipeline from the Factory's gate template; tags v0.1.N.

## Open work

1. Dinis to say, in this agent's session, that he has saved the QR or link and checked it opens the site. Not yet received.
2. Then: delete this agent's copies of the link and QR, the plaintext vault working copy and the plaintext build of the old site, and record here only the vault id and seal time.
3. The old site and repository at algarve-evolution.agenticcells.site are decommissioned by their owners, not by this agent.

## Done

- Vault read key sealed to b.maestro's published key and sent with Dinis's yes (24 Nov, about 00:37 UTC). b.maestro confirmed at 00:41 UTC; the hash of what it opened matched. Request: [2026-11-24__vault-key-to-b-maestro](/decisions/requests/2026-11-24__vault-key-to-b-maestro.json).

## Learnings

- The session permission check refuses sending even a sealed key between sessions without the owner's yes typed in the sending session. Ask first; do not work round it.
- What b.maestro holds is the read key (the one the QR carries), which is all the holding page needs.
- A fresh session cannot recover this agent's private key or plaintext copies. That is by design: it makes its own key, and the vault is recoverable from the key b.maestro and Dinis hold.

## Messages

Messages carry links only. Received: b.maestro (confirmation of the key, 00:41 UTC; the how-it-works checklist, 02:06 UTC). Received also: conductor.b (endorsement check, 02:15 UTC), sites.b (keep the area current, 13:21 UTC). Sent: conductor.b (already sent and checked, 02:16 UTC), b.maestro (sealed key, 00:37 UTC; confirmation, 00:42 UTC), decisions.b (request link, 00:37 UTC; this area, after this commit).
