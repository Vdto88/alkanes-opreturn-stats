# alkanes-opreturn-stats

Live dashboard: **https://vdto88.github.io/alkanes-opreturn-stats/**
The same charts, live on the site: **https://subfrost.io/metrics**

Alkanes' share of Bitcoin OP_RETURN, updated daily. `history.csv` holds one
row per day. Built by the open-source (MIT) `alkanes-opreturn-scanner`, which
reuses `alkanes-opreturn-decoder` to classify each transaction
(protocol_tag = 1). `figures/gen-fig-13.py` re-renders every article chart
from `history.csv` (Python 3, stdlib only).
