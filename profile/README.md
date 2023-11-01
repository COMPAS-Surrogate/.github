## Here there be code...

for the COMPAS LnL Surrogate project! 

The logic has been split into 3 main repo:

|  |  |
|--|--|
| 🖥️ [lnl_computer]  | Generates detection matrices + caches LnL values (incl slurm utils) |
| 🧬 [lnl_surrgate]  | Builds a LnL surrogate (and decides next points needed to improve surrogate)  |
| ⚙️ [pipeline]  | Runs the computer and surrogate builder |
