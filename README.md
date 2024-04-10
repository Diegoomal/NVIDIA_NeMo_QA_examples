# NVIDIA | NeMo | QA

## Datasets: 

1. SQuAD v2.0
2. MS-MARCO

## Models

1. BERT
2. S2S BART
3. GPT2

## Example files

1. src/SQuADv20_BERT.ipynb
2. src/SQuADv20_S2SBART.ipynb
3. src/SQuADv20_GPT2.ipynb
4. src/MSMARCO_S2SBART.ipynb

## Execute

```

conda activate NeMo-QA-env

conda env create -n NeMo-QA-env -f ./env.yml

conda env update -n NeMo-QA-env -f ./env.yml

conda env remove --n NeMo-QA-env

python src/main.py

```

## Ref. Links

[github](https://github.com/Diegoomal)

[1](https://docs.nvidia.com/nemo-framework/user-guide/latest/nemotoolkit/starthere/tutorials.html)

[2](https://colab.research.google.com/github/NVIDIA/NeMo/blob/stable/tutorials/nlp/Question_Answering.ipynb#scrollTo=PucJwfbhVC3L)