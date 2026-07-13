# Asset Manifest

All filenames in this directory are short, portable aliases for evidence preserved in the private research workspace.

## Media

- `bendpick-positive.*`: scripted MotionPlannerAgent raises the object, but the run does not pass the 0.5 s stable-lift criterion.
- `bendpickplace-attempt.*`: complete scripted BendPickAndPlace attempt; placement does not complete.
- `bendpick-stationary-trace.*`: BendPick diagnostic trace that violates the provisional stationary envelope.
- `rescue-state{1,2,3}-fail.*`: paired branches with a preregistered `+0.30 rad` right-shoulder pitch target bias from step 120.
- `rescue-state{1,2,3}-corrected.*`: paired branches that replay the original upper-body targets.
- `mcc-twist2-only-seed10.mp4`: readable seed-10 fixed-base TWIST2-only trajectory.
- `mcc-twist2-plus-mcc-seed10.mp4`: readable seed-10 fixed-base TWIST2+MCC trajectory.
- `mcc-paired-contact-impulse.png`: paired contact-impulse comparison across ten conditions.
- `mcc-median-force-trace.png`: median force trace for the paired comparison.

Each base-name `jpg` is a contact sheet. Each `mp4` is the corresponding H.264 rollout. Files ending in `-poster.jpg` are locally extracted final-frame video posters used by the HTML player.

## Machine-readable evidence

- `benchmark-selection-overview.html`: public-safe overview of the research question, selection evidence, adversarial corrections, and current conclusion.
- `task-selection-criteria.html`: public-safe task admission criteria distilled from the current seven-gate contract.
- `benchmark-candidate-evidence.html`: current evidence and counterevidence for BendPick, stationary OpenFaucet, and G1 Powerlift; supersedes the old provisional PASS labels.
- `benchmark-candidate-diagnostics.html`: BendPick measured-motion counterevidence and fixed-version OpenFaucet action/evaluator source inspection.
- `benchmark-evaluator-validation.html`: BendPick and OpenFaucet evaluator criteria and human-readable results for 36 evaluator tests.
- `benchmark-evaluator-test-summary.json`: machine-readable results for 20 BendPick, 14 OpenFaucet, and 2 identity-binding tests.
- `bendpick-stationary-evaluation.json`: exactification evaluation and claim boundary.
- `upper-body-rescue-verification.json`: three-pair isolation checks, stock-task instantaneous-lift result, and explicit strict stable-lift boundary.
- `bendpick-upper-body-rescue-report.html`: public-safe report for the three state-locked BendPick upper-body correction pairs.
- `openfaucet-controller-audit.html`: public-safe report for four frozen OpenFaucet joint-PD/IK trajectories.
- `openfaucet-controller-verification.json`: public-safe machine summary of the four strict OpenFaucet evaluations.
- `dynamic-candidate-independent-review.html`: independent publication review of source/result consistency, evaluator tests, and claim boundaries.
- `trajectory-interface-report.html`: public-safe report for the two-platform, four-trajectory recording and evaluation interface.
- `trajectory-interface-independent-qa.html`: independent rerun, reproducibility and scientific-boundary review for the interface delivery.
- `trajectory-interface-acceptance.json`: final public-safe machine summary covering four real trajectories, 37 tests, semantic/source tamper rejection and cross-runtime reproducibility.
- `mcc-component-smoke-result.json`: zero-wrench MCC component smoke result.
- `mcc-hard-effect-report.html`: fixed-base TWIST2-only / TWIST2+MCC hard-effect report with public-safe evidence links.
- `mcc-independent-qa.html`: independent result and claim-boundary audit.
- `mcc-aggregate-metrics.json`: aggregate results for ten paired conditions.
- `mcc-paired-metrics.csv`: per-condition paired metrics.
- `mcc-machine-qc-summary.json`: hash, pairing, trajectory and numeric-field checks.
- `mcc-video-qc.json`: readable-video integrity checks.
- `mcc-adapter-test-result.json`: seven automated adapter checks.

The copied evidence files were scanned for local user paths, hostnames, credentials, and personal names before inclusion.
