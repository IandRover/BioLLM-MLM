# BioLLM-MLM

## Evaluation of Nucleotide Transformer with MLM

This repository provides tools and scripts for evaluating the Nucleotide Transformer using Masked Language Modeling (MLM).

### Installation

To install the required packages, run: `pip install -r requirements.txt`

### Usage

You can run the main script using: `python run_mlm.py `

Alternatively, for an interactive experience, open the notebook `v0_0_1_Aaron_Implementation.ipynb` using Google Colab or your preferred Jupyter environment.

### Useful Links

- [InstaDeep HuggingFace Page](https://huggingface.co/InstaDeepAI)
- Model and tokenizer links can be found [here](https://huggingface.co/InstaDeepAI/nucleotide-transformer-500m-human-ref/blob/main/README.md):
  - `tokenizer = AutoTokenizer.from_pretrained("InstaDeepAI/nucleotide-transformer-500m-human-ref")`
  - `model = AutoModelForMaskedLM.from_pretrained("InstaDeepAI/nucleotide-transformer-500m-human-ref")`
- [Dataset Information](https://huggingface.co/datasets/InstaDeepAI/human_reference_genome)
