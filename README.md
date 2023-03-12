# Multimodal Embeddings for Information Coordination Detection

## Fabio's branch
On this branch, you'll find:
- `merge_datasets.ipynb`: a notebook that attempts to merge the datasets together. (WIP)
- `fabio_eda.ipynb`: EDA notebook that also attempts to do topic extraction. You're probably looking for this notebook. Also contains hand-written description of each dataset.
- `eda_output`: folder containing the output of the EDA notebook.

Python packages necessary to run the notebook can be found in `requirements.txt`. Let me know if I forgot any.

**This requires you to have downloaded the twitter data and placed it in the `twitter_data` folder**. It can't be uploaded to github since it's too large (10GB).

### To-do
- [ ] make dataset of english-only tweets
- [ ] Finish running EDA on all datasets

### Wanna help out?
Some todos can be found in the eda notebook (Introduction section).

Things you can research/improve:
- [ ] Topic Extraction methods:
    - [ ] understand Latent Dirichlet Allocation (LDA) - currently used in the notebook
    - [ ] find other methods
- [ ] Tweet embeddings: explore other methods to embed tweets

**PLEASE DON'T PUSH TO MY BRANCH (unless you're allowed to do so :) )**