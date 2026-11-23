# Crew Countdown Clock firmware

**Setting up a new clock?** Open https://crewclock.163-192-127-148.sslip.io/ in Chrome or Edge on a computer.

Signed firmware images for the Crew Countdown Clock, published automatically.
Clocks check `stable.json` or `beta.json` daily and install newer versions after
verifying the ECDSA P-256 signature over `version\nsize\nsha256\n`.
`firmware/VERSION-full.bin` is the complete 4 MB image the install page flashes at offset 0.

Nothing to do here by hand: releases come from the private source repo's Actions.
