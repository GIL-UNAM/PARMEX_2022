# PARMEX 2022
## PARAPHRASE IDENTIFICATION IN MEXICAN SPANISH

### IMPORTANT
Due to a problem we found in the script we used to separate the paraphrased sentences into training, validation, and testing all datasets were updated, so you will need to train again the models and then perform the predictions on the new development and test sets.

Check our codalab page [HERE](https://codalab.lisn.upsaclay.fr/competitions/2345).

### Task Description
In this task participants will be given pairs of sentences and the aim is to indicate whether each pair captures a paraphrase relationship, i.e. to classify them as paraphrases (P) or not paraphrases (NP).

Full task details [here](https://sites.google.com/view/par-mex/home).

### Corpus
The distribution of the corpus is shown in the following table:

| Corpus | Total sentence-pairs | Paraphrase sentence-pairs | Non-paraphrase sentence-pairs 
| --- | --- | --- | --- |
| Training | 7601 (100%) | 1501 (20%) | 6100 (80%) |
| Validation | 100 (100%) | 23 (23%) | 77 (77%) |

The labels for each sentence-pair are the following:
 * 1: Paraphrase (P)
 * 0: Non-paraphrase (NP)
