# Neural Machine Translation Methods for Translating Text to Sign Language Glosses

This repository provides complementary material to aid the replication of the experiments described in the thesis work of  [Neural Machine Translation Methods for Translating Text to Sign Language Glosses].


## Introduction


## Content 

The structure of the repository is as following:

 * `notebooks`: Python notebooks containing the code for reproducing the experiments, 
   *  splitting training and test set for the DGS corpus
   *  measuring statistics for the DGS corpus
   *  extract glosses and german intepretation from the DGS corpus
   *  custom tokenization of the DGS corpus
   *  measure overlap between training, dev and test splits of the DGS corpus
 * `training scripts`: bash files including SLURM commands to execute Marian-NMT for training the NMT models reported in the paper
 * `data`: the plain-text versions of the paraller corpora for both the DGS and the Phoenix corpora. It includes the training, dev and test split for both the Phoenix and DGS corpus. Additionally, one can find tokenized, stemmed and augmented versions as reported in the paper.  

Please note that the corpora ([Phoenix 2014T](https://www-i6.informatik.rwth-aachen.de/~koller/RWTH-PHOENIX-2014-T/) and [DGS Corpus](https://www.sign-lang.uni-hamburg.de/meinedgs/ling/start_en.html)) have their own licenses and any use of them should be conforming with them and include the appropriate citations. 

