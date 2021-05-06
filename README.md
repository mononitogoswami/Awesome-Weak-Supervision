# Awesome-Weak-Supervision [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of programmatic/rule-based weak supervision papers and resources.

## Contents
 - [Algorithm](#Algorithm)
 - [System](#Systems)
 - [Application](#Application)
 - [Thesis](#Thesis)

![An overview of weak supervision](https://github.com/JieyuZ2/Awesome-Programmatic-Weak-Supervision/blob/main/ws.png)


## Blogs
[An Overview of Weak Supervision](https://www.snorkel.org/blog/weak-supervision)

[Building NLP Classifiers Cheaply With Transfer Learning and Weak Supervision](https://medium.com/sculpt/a-technique-for-building-nlp-classifiers-efficiently-with-transfer-learning-and-weak-supervision-a8e2f21ca9c8)

## Lecture Notes
[Lecture Notes on Weak Supervision](http://narimanfarsad.com/cps803/docs/weak_supervision_notes.pdf)

## Algorithm
[Data Programming: Creating Large Training Sets, Quickly](https://arxiv.org/abs/1605.07723). Alex Ratner ```NeurIPS 2016```

[Socratic Learning: Augmenting Generative Models to Incorporate Latent Subsets in Training Data](https://arxiv.org/abs/1610.08123). Paroma Varma ```FILM-NeurIPS 2016```

[Training Complex Models with Multi-Task Weak Supervision](https://arxiv.org/abs/1810.02840). Alex Ratner ```AAAI 2019```

[Data Programming using Continuous and Quality-Guided Labeling Functions](https://arxiv.org/abs/1911.09860). Oishik Chatterjee ```AAAI 2020```

[Fast and Three-rious: Speeding Up Weak Supervision with Triplet Methods](https://arxiv.org/abs/2002.11955). Dan Fu ```ICML 2020```

[Learning from Rules Generalizing Labeled Exemplars](https://arxiv.org/abs/2004.06025). Abhijeet Awasthi ```ICLR 2020```

[Learning the Structure of Generative Models without Labeled Data](https://arxiv.org/abs/1703.00854). Stephen H. Bach ```ICML 2017```

[Inferring Generative Model Structure with Static Analysis](https://papers.nips.cc/paper/2017/file/cedebb6e872f539bef8c3f919874e9d7-Paper.pdf). Paroma Varma ```NeurIPS 2017```

[Learning Dependency Structures for Weak Supervision Models](https://arxiv.org/abs/1709.01643). Paroma Varma ```ICML 2019```

[Self-Training with Weak Supervision](https://arxiv.org/abs/2104.05514). Giannis Karamanolakis ```NAACL 2021```

[Interactive Programmatic Labeling for Weak Supervision](https://bencw99.github.io/files/kdd2019_dcclworkshop.pdf). Benjamin Cohen-Wang ```KDD Workshop 2019```

[Pairwise Feedback for Data Programming](https://arxiv.org/abs/1912.07685). Benedikt Boecking ```NeurIPS 2019 workshop on Learning with Rich Experience: Integration of Learning Paradigms```

[Interactive Weak Supervision: Learning Useful Heuristics for Data Labeling](https://arxiv.org/abs/2012.06046). Benedikt Boecking ```ICLR 2021```

[Active WeaSuL: Improving Weak Supervision with Active Learning](https://arxiv.org/abs/2104.14847). Samantha Biegel ```ICLR WeaSuL 2021```

## System
[Snorkel: Rapid Training Data Creation with Weak Supervision](https://arxiv.org/abs/1711.10160). Alex Ratner ```VLDB 2018```

[Snorkel DryBell: A Case Study in Deploying Weak Supervision at Industrial Scale](https://arxiv.org/abs/1812.00417). Stephen H. Bach ```SIGMOD (Industrial) 2019```

[Snuba: Automating Weak Supervision to Label Training Data](http://www.vldb.org/pvldb/vol12/p223-varma.pdf). Paroma Varma ```VLDB 2019```

## Application

### CV
[Scene Graph Prediction with Limited Labels](https://arxiv.org/pdf/1904.11622.pdf). Vincent Chen ```ICCV 2019```

[Multi-Resolution Weak Supervision for Sequential Data](https://arxiv.org/pdf/1910.09505.pdf). Paroma Varma ```NeurIPS 2019```

[GOGGLES: Automatic Image Labeling with Affinity Coding](https://arxiv.org/abs/1903.04552). Nilaksh Das ```SIGMOD 2020```

[Cut out the annotator, keep the cutout: better segmentation with weak supervision](https://openreview.net/pdf?id=bjkX6Kzb5H). Sarah Hooper ```ICLR 2021```

### NLP
[Heterogeneous Supervision for Relation Extraction: A Representation Learning Approach](https://arxiv.org/abs/1707.00166). Liyuan Liu ```EMNLP 2017```

[Training Classifiers with Natural Language Explanations](https://arxiv.org/abs/1805.03818). Braden Hancock ```ACL 2018```

[Deep Text Mining of Instagram Data without Strong Supervision](https://ieeexplore.ieee.org/abstract/document/8609589/authors#authors). Kim Hammar ```ICWI 2018```

[Bootstrapping Conversational Agents With Weak Supervision](https://arxiv.org/pdf/1812.06176.pdf). Neil Mallinar ```AAAI 2019```

[Weakly Supervised Sequence Tagging from Noisy Rules](http://cs.brown.edu/people/sbach/files/safranchik-aaai20.pdf). Esteban Safranchik ```AAAI 2020```

[NERO: A Neural Rule Grounding Framework for Label-Efficient Relation Extraction](https://arxiv.org/abs/1909.02177). Wenxuan Zhou ```WWW 2020```

[Named Entity Recognition without Labelled Data: A Weak Supervision Approach](https://arxiv.org/abs/2004.14723). Pierre Lison ```ACL 2020```


### Others
[Generating Training Labels for Cardiac Phase-Contrast MRI Images](https://www.paroma.xyz/). Vincent Chen ```MED-NeurIPS 2017```

[Osprey: Weak Supervision of Imbalanced Extraction Problems without Code](https://ajratner.github.io/assets/papers/Osprey_DEEM.pdf). Eran Bringer ```SIGMOD DEEM Workshop 2019```

[Weakly Supervised Classification of Rare Aortic Valve Malformations Using Unlabeled Cardiac MRI Sequences](https://jdunnmon.github.io/mri_biorxiv.pdf). Jason Fries ```Nature Communications 2019```

[Doubly Weak Supervision of Deep Learning Models for Head CT](https://link.springer.com/chapter/10.1007/978-3-030-32248-9_90). Khaled Saab ```MICCAI 2019```

[A clinical text classification paradigm using weak supervision and deep representation](https://bmcmedinformdecismak.biomedcentral.com/articles/10.1186/s12911-018-0723-6). Yanshan Wang ```BMC MIDM 2019```

[A machine-compiled database of genome-wide association studies](https://www.nature.com/articles/s41467-019-11026-x). Volodymyr Kuleshov ```Nature Communications 2019```

[Weak Supervision as an Efficient Approach for Automated Seizure Detection in Electroencephalography](https://jdunnmon.github.io/ndm-final.pdf). Khaled Saab ```NPJ Digital Medicine 2020```

[Extracting Chemical Reactions From Text Using Snorkel](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-020-03542-1). Emily Mallory ```BMC Bioinformatics 2020```

[Cross-Modal Data Programming Enables Rapid Medical Machine Learning](https://arxiv.org/abs/1709.01643). Jared A. Dunnmon ```Patterns 2020```

[SwellShark: A Generative Model for Biomedical Named Entity Recognition without Labeled Data](https://arxiv.org/abs/1704.06360). Jason Fries

[Ontology-driven weak supervision for clinical entity classification in electronic health records](https://arxiv.org/abs/2008.01972). Jason Fries ```Nature Communications 2021```

[Utilizing Weak Supervision to Infer Complex Objects and Situations in Autonomous Driving Data](https://ieeexplore.ieee.org/abstract/document/8814147). Zhenzhen Weng ```IV 2019```

[Multi-frame Weak Supervision to Label Wearable Sensor Data](http://roseyu.com/time-series-workshop/submissions/2019/timeseries-ICML19_paper_44.pdf). Saelig Khattar ```ICML Time Series Workshop 2019```


## Thesis
[Acclerating Machine Learning with Training Data Management](https://ajratner.github.io/assets/papers/thesis.pdf). Alex Ratner

[Weak Supervision From High-Level Abstrations](https://stacks.stanford.edu/file/druid:ns523jd4552/hancock_dissertation_vsubmission-augmented.pdf). Braden Jay Hancock
