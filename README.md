# MCFM Dataset

Where "MCFM" stands for "Multilingual, Culture-First Misgendering" dataset. It's too long to write it as the title anyway. 

This repository contains the data used in the paper "[A Multilingual, Culture-First Approach to Addressing Misgendering in LLM Applications
](https://arxiv.org/abs/2503.20302)", by Sunayana Sitaram, Adrian de Wynter, Isobel McCrum, Qilong Gu, and Si-Qing Chen. 

This dataset addresses the issue of misgendering by generative models, such as LLMs, in a multilingual/multicultural scenario. Currently it supports 42 languages and dialects.

The core contributions of our work are:
- Guardrails to mitigate misgendering (more on that in a bit)
- A set of data in these 42 languages and dialects modelling meeting transcripts where at least one participant has their preferred pronouns/gender unspecified or ambiguous.
- Human-annotated data over a subset of these transcripts
- Bonus: LLM-annotated data. Please note that one of our main findings in our paper is that LLMs-as-judges fail to detect misgendering, albeit guardrails are effective.

The construction of the guardrails followed strict participatory design practices: we first used a set of public [guidelines](https://learn.microsoft.com/en-us/style-guide/bias-free-communication) to build our first pass, but then polled native speakers on the validity of these guardrails. Then we edited them out based on their feedback.
This means that these guardrails are not necessarily modelling (Western) English sociocultural concerns, but are still relevant and achieving their goal in the locale.


## Citation

If you used our work in yours, here's the bibtex to make your life easier:

```
@misc{sitaram2025multilingualculturefirstapproachaddressing,
      title={A Multilingual, Culture-First Approach to Addressing Misgendering in LLM Applications}, 
      author={Sunayana Sitaram and Adrian {de Wynter} and Isobel McCrum and Qilong Gu and Si-Qing Chen},
      year={2025},
      eprint={2503.20302},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2503.20302}, 
}
```

## Contributing and Trademarks

See [here](CONTRIBUTING.md).

## License

CDLA-2.0, which is like MIT but for data. Our lawyers asked for it. See [here](LICENSE.md).
