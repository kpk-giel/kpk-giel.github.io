# kpk-giel.github.io

`/btc-carry-dashboard/` mirrors the BTC Carry board from kpk-labs/btc-carry-dashboard, pulled hourly by `.github/workflows/pull-board.yml`. This is temporary while https://external.kpk.io/btc-carry-fund/ (the main link) can't deploy, since 22 Oct 2026. Once it deploys again, restore the redirect page from commit ba914d3.

`/upshift-lseth-dashboard/` forwards to https://kpk-labs.github.io/upshift-lseth-dashboard/ since the repo moved to kpk-labs (23 Oct 2026). Once external.kpk.io serves the board itself (external-resources PR replacing its redirect), point this at https://external.kpk.io/upshift-lseth-dashboard/ instead; pointing it there earlier would loop, as external.kpk.io still forwards here.
