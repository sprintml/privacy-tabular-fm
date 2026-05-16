# Evaluation harness

Scoring functions used by the leaderboard server. Submissions are
CSV files of predicted probabilities; scoring is a pure function of
the submitted file plus the held-out ground truth.

- `tpr_at_fpr.py` — TPR @ 1% FPR with bootstrapped 95% confidence
  intervals (Tracks 2 - 4, per proposal §1.5).
- `ovo_macro_auc.py` — one-vs-one macro-averaged ROC AUC
  (Track 1, per proposal §1.5 update).

The competition server runs these functions against a fixed held-out
split; participants can run the same functions locally on the public
split via the starting kit.

