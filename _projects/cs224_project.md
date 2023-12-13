---
title: "Linear Bandits with Total Variation Contamination"
excerpt: "Harvard Computer Science 224 Final Project"
collection: projects
---

[Link Here](/files/cs224_final_project.pdf)

The linear bandit problem with adversarial corruptions is a variant of the standard stochastic linear bandit problem where the agent observes a reward corrupted by an adversary, rather than one stochas- tically drawn from the environment. Such an adversary has been proposed with Huber contamination [Chen et al., 2022] and strong contamination with bounded rewards [Kapoor et al., 2019]. In this expository work, we specifically focus on total variation (TV) contamination: the formulation of adversarial corruptions where the adversary can change the rewards arbitrarily at every round; however, there is a fixed budget C for the total difference the rewards can change [Zhao et al., 2021]. We offer a deep dive of the analysis presented in [Zhao et al., 2021] for the Robust Weighted OFUL algorithm, an algorithm designed to achieve robust performance in the TV-contamination setting.

