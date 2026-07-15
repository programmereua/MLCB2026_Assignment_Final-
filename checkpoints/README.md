# Model checkpoints

This directory contains the final saved model states used in the reported analyses.

## Celcomen

- celcomen_HM11_seed0.pt
- celcomen_T11_seed0.pt

These files contain the seed-0 fitted Celcomen model states for the HM11 and T11 sections.

## Attention Model 4

- HM11_stochastic_attention_seed_0.pt
- T11_stochastic_attention_seed_0.pt

These files contain the one-seed stochastic attention model states used in the constant-row-mass attention analysis.

The FCI files are stored separately under outputs/Causality/serialized_results because they contain serialized analysis results rather than trained neural-network checkpoints.

PyTorch and pickle files should only be loaded from trusted sources and using compatible software versions.
