# DIN

Chinese translation of *Deep Interest Network for Click-Through Rate Prediction* (KDD'18), by Guorui Zhou, Chengru Song, Xiaoqiang Zhu, et al. (Alibaba Group).

## Structure

- `DeepInterestNetwork.tex` — main document (based on the `acmart` class)
- `ch_intro.tex` — introduction
- `ch_relatedwork.tex` — related work
- `ch_approach.tex` — proposed approach (DIN)
- `ch_sysview.tex` — system view
- `ch_exp.tex` — experiments
- `ch_concln.tex` — conclusion
- `images/` — figures used in the paper

## Build

The document requires `xelatex` for CJK support. The bibliography (`DeepInterestNetwork.bbl`) is pre-generated and checked in, so `bibtex` is not needed:

```sh
xelatex DeepInterestNetwork.tex
xelatex DeepInterestNetwork.tex
```

## License

This is an unofficial translation for study purposes. All rights to the original paper belong to its authors.
