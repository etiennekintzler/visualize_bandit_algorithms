# Visual interpretation of bandit algorithms

![alt text](https://paperswithcode.com/media/tasks/multiarmedbandit_mSsuHAy.jpg)

This goal of this repo is to offer some visual interpretation of bandit algorithms output.

There are currently 2 notebooks:

- [linUCB.ipynb](./linUCB.ipynb):  LinUCB algorithm (disjoint model case) from [A Contextual-Bandit Approach to Personalized News Article Recommendation (Li et al 2010 )](https://arxiv.org/pdf/1003.0146)

- [bandit_model_selection.ipynb](./bandit_model_selection.ipynb): Bandits are used for online model selection. This feature is for now experimental. It relies heavily on the Python online ML library [river](https://github.com/online-ml/river/). This notebook might not be reproducible at the moment since this feature is not yet fully merged in the library.
