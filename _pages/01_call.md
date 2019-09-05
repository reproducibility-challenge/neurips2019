---
layout: page
permalink: /task/
title: Task Description
---

You should select a paper from the [2019 NeurIPS](https://nips.cc/Conferences/2019/) [accepted papers](https://neurips.cc/Conferences/2019/AcceptedPapersInitial), and aim to replicate the experiments described in the paper. The objective is to assess if the experiments are reproducible, and to determine if the conclusions of the paper are supported by your findings. Your results can be either positive (i.e. confirm reproducibility), or negative (i.e. explain what you were unable to reproduce, and potentially explain why).

**Essentially, think of your role as an inspector verifying the validity of the experimental results and conclusions of the paper. In some instances, your role will also extend to helping the authors improve the quality of their work and paper.**

You do not need to reproduce all experiments in your selected paper, for example the authors may experiment with a new method that requires more GPUs than you have access to, but also present results for a baseline method (e.g. simple logistic regression), in which case you could elect to reproduce only the baseline results. It is sometimes the case that baseline methods are not properly implemented, or hyper-parameter search is not done with the same degree of attention.

If available, the authors’ code can and should be used; authors of NeurIPS submissions are encouraged to release their code to facilitate this challenge. The methods described can also be implemented/re-implemented according to the description in the paper. This is a higher bar for reproducibility, but may be helpful in detecting anomalies in the code, or shedding light on aspects of the implementation that affect results.

## Tracks

For NeurIPS Reproducibility Challenge, we have three tracks for submission to the workshop:

1. **Baselines Track** : In this track, your role is to reproduce and inspect the performance of the baselines reported in the paper. You should be able to re-implement / re-verify the baselines and perform rigorous ablations / hyper-parameter tuning on the baselines reported in the paper.

2. **Ablation Track** : In this track, your role is to use the released code-base of the authors, and perform rigorous ablation studies and hyper-parameter explorations on it. You should back your report with insights gathered from well targeted ablations and their consequences on the overall model behavior.

3. **Replication Track** : Here, your role is to perform exact replication of the presented main results of the paper _from scratch_, i.e. you should not use any code which were released by the authors (if any). The objective of this track is to analyze the replicability of the presented idea just by reading the paper and supplementary materials.

## Proposed outcomes

- The goal of this challenge is **not** to criticize papers or the hard work of our fellow researchers. [Science is not a competitive sport](https://www.facebook.com/nipsfoundation/videos/2120856364798049/). Thus, the main objective of this challenge is to provide a fun learning exercise for newcomers in the Machine Learning field, while contributing to the research by strengthening the quality of the original paper.
- Participants should produce a Reproducibility report, describing the target questions, experimental methodology, implementation details, analysis and discussion of findings, conclusions on reproducibility of the paper. This report should be posted as a contributed review on OpenReview.
- The result of the reproducibility study should NOT be a simple Pass / Fail outcome. The goal should be to identify which parts of the contribution can be reproduced, and at what cost in terms of resources (computation, time, people, development effort, communication with the authors).
- Participants should expect to engage in dialogue with NeurIPS authors through the OpenReview site. We will announce shortly where the accepted Reproducibility Reports will be published.  
