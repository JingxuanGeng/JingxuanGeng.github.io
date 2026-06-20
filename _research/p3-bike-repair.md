---
title: "Sequential Diagnosis Under Piece-Rate Incentives: When a Second Opinion Does (Not) Help"
permalink: /research/p3-bike-repair
excerpt: with Hailong Cui, Guangwen Kong. _Revising_ _for_ _submission_ _to_ **_Manufacturing_ _&_ _Service_ _Operations_ _Management_**
---

Hailong Cui, Jingxuan Geng, Guangwen Kong(Alphabetical Order)

_Under_ _review_ _at_ **_Manufacturing_ _&_ _Service_ _Operations_ _Management_**


[SSRN Link](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5504778)

**Problem definition**: Bike-sharing platforms incur substantial maintenance costs, driven not only by heavy usage but also by inefficient diagnostic decisions on whether a defective part should be repaired or replaced. This setting shares a common structure with service operations such as equipment maintenance, automotive inspection, and healthcare triage: a preliminary diagnosis and the resulting treatment decision are made by different agents, and the treatment-performing agent is paid a piece rate that rewards intervention. In such operations, sequential "second-opinion" review is advocated as a check on piece-rate-driven over-treatment. We examine when the second opinion actually adds value, and when it merely duplicates work that correcting the incentive would already accomplish. **Methodology/results**: We formalize sequential diagnosis as a two-stage Bayesian game and recover agent-level skill and behavioral factors from observed decisions by maximizing a likelihood subject to Bayesian Nash Equilibrium (BNE) constraints. A machine-learning-assisted approach (a neural-network surrogate) resolves the resulting computational challenge. Applied to task-level data from a leading bike-sharing platform (100,752 bikes; 294,949 defective parts), the framework attributes systematic over-replacement not to low skill but to piece-rate incentives propagated through an equilibrium feedback loop between the agents. **Managerial implications**: The value of the second opinion is contingent on whether incentives are corrected. When they are not, such as at the platform's focal piece rate, the two-stage system is less costly than a one-stage alternative because it filters significant incentive-driven over-replacement. When the piece rate is set optimally, however, the one-stage system is found to be 4.45% cheaper despite a 0.79% reduction in decision accuracy. Piece-rate restructuring delivers the largest single-lever effect, while two further levers, including structured matching and targeted training, contribute additively. The implication is that the choice between one stage and two, and the choice of piece-rate level, should be made jointly: a second opinion is valuable when the piece-rate incentive is high, but its advantage diminishes once the wage can be set optimally based on the (unobservable) skill and behavioral factors that our framework recovers.

