# Seedling Dataset Note

This repo includes `labels.csv`, and the trained CNN is included separately in `../models/seedling_classifier_model.keras`, but the full `images.npy` array was not copied into the GitHub staging set because it is larger than normal GitHub file limits.

To make the notebook fully runnable, add:
- `data/39af014a165dbbdd9d14eaadbab26cda/images.npy`

Best options:
- Git LFS
- external download link plus instructions
- smaller sample dataset for public demo

For the current staged repo:
- reviewers can inspect or load the trained model without retraining
- full notebook retraining still requires `images.npy`
