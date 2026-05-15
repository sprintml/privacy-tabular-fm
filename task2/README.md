# TASK 2: Membership Inference

Membership Inference Attacks determine whether an individual record was part of the training set of a target model. The track targets a TFM conditioned on a private in-context training set. For each of [N] candidate records, drawn from a mixture of members and non-members in fixed but unknown proportions, the participants submit a membership probability for each candidate record. Real-world analog: a record subject seeks to verify whether their personal record appears in the in-context training set of a TFM deployed without their consent.
