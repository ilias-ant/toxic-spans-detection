# toxic-spans-detection
An attempt at the [SemEval 2021 Task 5: Toxic Spans Detection](https://competitions.codalab.org/competitions/25623#learn_the_details-overview).

<img src="static/semeval.png" alt="all rights reserved by CodaLab" width="500"/>

The Toxic Spans Detection task of SemEval2021 required participants to predict the spans of toxic posts that were responsible for the toxic label of the posts. You can read the [task overview paper](https://aclanthology.org/2021.semeval-1.6.pdf) for more information about the task, data, evaluation, and performance of the participating systems.

## Installation

```shell
python3.8 -m pip install poetry
```

and then:

```shell
python3.8 -m poetry install
```

To serve the Jupyter notebooks, available under `notebooks/`, run:

```shell
python3.8 -m poetry run jupyter notebook
```

## Evaluation

The team that has ranked first in this competition (HITSZ-HLT) has achieved an $ F_1 $ score of $ 70.83 \% $, with the median score across all 36 participating teams being $ 67.58 \% $.

Our approach, as presented here, yields: $ 64.46 \%$.