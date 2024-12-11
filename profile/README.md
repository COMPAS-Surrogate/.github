## Here there be code...
for the COMPAS LnL Surrogate project! 

The logic has been split into a few main repos:

|  |  |
|--|--|
| 🖥️ [lnl_computer]  | Generates detection matrices + caches LnL values (incl slurm utils) |
| 🧬 [lnl_surrogate]  | Builds a LnL surrogate (and decides next points needed to improve surrogate)  |
| ⚙️ [pp_test]  | Runs the computer and surrogate builder for numerous simulations|
| 📖 [ogc4_interface]  | Interface to OGC4 GW catalog|


[lnl_computer]: https://github.com/COMPAS-Surrogate/lnl_computer
[lnl_surrogate]: https://github.com/COMPAS-Surrogate/lnl_surrogate
[pp_test]: https://github.com/COMPAS-Surrogate/pp_test
[ogc4_interface]: https://github.com/COMPAS-Surrogate/ogc4_interface

There are some more non-essential repos for the project
- [paper](https://github.com/COMPAS-Surrogate/paper)
- [active learning experiments](https://github.com/COMPAS-Surrogate/active_learning_experiments)
- [surrogate_studies](https://github.com/COMPAS-Surrogate/surrogate_studies)

[Wiki with meeting mins here](https://avi-vajpeyi.gitbook.io/compas-ml-surrogate/)
