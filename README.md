# Crew Countdown Clock firmware

Signed firmware images for the Crew Countdown Clock, published automatically.
Clocks check `stable.json` or `beta.json` daily and install newer versions after
verifying the ECDSA P-256 signature over `version\nsize\nsha256\n`.

Nothing to do here by hand: releases come from the private source repo's Actions.
