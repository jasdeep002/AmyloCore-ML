# AmyloCore-ML
Prediction of amyloid cores from sequences
# AmyloCore-ML

AmyloCore-ML predicts residue-level incorporation into
structurally resolved amyloid fibril cores from protein sequence
using ESM-2 and Ankh protein language models.

## Run AmyloCore-ML

[Open AmyloCore-ML in Google Colab](https://colab.research.google.com/github/jasdeep002/AmyloCore-ML/blob/main/AmyloCoreML.ipynb)

No local installation is required.

### Inputs

- UniProt accession or protein sequence
- ESM-2, Ankh, or both
- W9, W15, W21, or all windows
- CORE probability threshold

### Outputs

- residue-level CORE probabilities
- predicted CORE segments
- interactive probability profiles
- downloadable CSV files
