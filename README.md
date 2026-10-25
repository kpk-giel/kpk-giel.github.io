# kpk-giel.github.io

`/btc-carry-dashboard/` forwards to https://external.kpk.io/btc-carry-fund/, which deploys again. The hourly mirror (22-25 Oct 2026) is removed: kpk-labs/btc-carry-dashboard went private, so its raw file 404'd and every pull failed.

`/upshift-lseth-dashboard/` forwards to https://kpk-labs.github.io/upshift-lseth-dashboard/ since the repo moved to kpk-labs (23 Oct 2026). Once external.kpk.io serves the board itself (external-resources PR replacing its redirect), point this at https://external.kpk.io/upshift-lseth-dashboard/ instead; pointing it there earlier would loop, as external.kpk.io still forwards here.
