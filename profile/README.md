## Here there be code...
for the COMPAS LnL Surrogate project! 

The logic has been split into 3 main repos:

|  |  |
|--|--|
| 🖥️ [lnl_computer]  | Generates detection matrices + caches LnL values (incl slurm utils) |
| 🧬 [lnl_surrogate]  | Builds a LnL surrogate (and decides next points needed to improve surrogate)  |
| ⚙️ [pipeline]  | Runs the computer and surrogate builder |


[lnl_computer]: https://github.com/COMPAS-Surrogate/lnl_computer
[lnl_surrogate]: https://github.com/COMPAS-Surrogate/lnl_surrogate
[pipeline]: https://github.com/COMPAS-Surrogate/pipeline

There are some more non-essential repos for the project
- [paper](https://github.com/COMPAS-Surrogate/paper)
- [active learning experiments](https://github.com/COMPAS-Surrogate/active_learning_experiments)
- [surrogate_studies](https://github.com/COMPAS-Surrogate/surrogate_studies)

