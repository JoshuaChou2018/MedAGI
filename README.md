# MedAGI: pick up the most suitable domain-specific alignment layer for you

[Juexiao Zhou#](https://www.joshuachou.ink/), Xiuying Chen#, Xin Gao

King Abdullah University of Science and Technology, KAUST

<a href='xxx.pdf'><img src='https://img.shields.io/badge/Paper-PDF-red'></a>

## Installation

```shell
conda env create -f environment.yml
conda activate medagi
```

## Preparation of Domain-specific Alignment layers

To train your domain-specific layer, please follow the steps at https://github.com/Vision-CAIR/MiniGPT-4

Then set the model path and model description at `` for each of your domain-specific alignment layers.

Now, you are ready to go! MedAGI will pick up the most suitable domain-specific alignment layer for you according to your inputs.

## Launching Demo Locally

```
python demo.py --cfg-path eval_configs/medagi_eval.yaml  --gpu-id 0
```

## To Contribute

We are open to accepting more domain-specific alignment layers! Please PR to add your domain-specific alignment layer and description. 

## Acknowledgement

- [MiniGPT-4](https://minigpt-4.github.io/) This repo is based on MiniGPT-4, an awesome repo for vision-language chatbot!
- Lavis
- Vicuna

## Citation

If you're using MedAGI in your research or applications, please cite both MedAGI using this BibTeX:

```
xxx
```
