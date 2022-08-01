# PEN: Problems with Explanations for Numbers

This is a repository for the dataset proposed in [EPTX](https://aclanthology.org/2022.acl-long.305/).

## How to run evaluation

- Please refer to the evaluation code in [EPTX repo](https://github.com/snucclab/ept-x)

## File structure

- `/dataset/pen.json` the PEN dataset
- `/experiments` Directory containing split specifications
    - `/experiments/pen` Directory containing splits of PEN dataset
    - `/experiments/draw` Directory containing splits of DRAW-1K dataset
    - `/experiments/alg514-fold*` Directory containing splits of ALG514-fold* dataset
    - `/experiments/mawps-fold*` Directory containing splits of MAWPS-fold* dataset
    - Each directory has train, test, and/or dev file.

## Citation

Whenever you use this code for any academic purpose, please cite the paper below.

```text
@inproceedings{kim-etal-2022-ept,
    title = "{EPT}-{X}: An Expression-Pointer Transformer model that generates e{X}planations for numbers",
    author = "Kim, Bugeun  and
      Ki, Kyung Seo  and
      Rhim, Sangkyu  and
      Gweon, Gahgene",
    booktitle = "Proceedings of the 60th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)",
    month = may,
    year = "2022",
    address = "Dublin, Ireland",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2022.acl-long.305",
    doi = "10.18653/v1/2022.acl-long.305",
    pages = "4442--4458",
    abstract = "In this paper, we propose a neural model EPT-X (Expression-Pointer Transformer with Explanations), which utilizes natural language explanations to solve an algebraic word problem. To enhance the explainability of the encoding process of a neural model, EPT-X adopts the concepts of plausibility and faithfulness which are drawn from math word problem solving strategies by humans. A plausible explanation is one that includes contextual information for the numbers and variables that appear in a given math word problem. A faithful explanation is one that accurately represents the reasoning process behind the model{'}s solution equation. The EPT-X model yields an average baseline performance of 69.59{\%} on our PEN dataset and produces explanations with quality that is comparable to human output. The contribution of this work is two-fold. (1) EPT-X model: An explainable neural model that sets a baseline for algebraic word problem solving task, in terms of model{'}s correctness, plausibility, and faithfulness. (2) New dataset: We release a novel dataset PEN (Problems with Explanations for Numbers), which expands the existing datasets by attaching explanations to each number/variable.",
}
```

