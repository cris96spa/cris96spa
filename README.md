# Hi, I'm Cristian

I'm an NLP engineer at Artificialy in Lugano, where I make large language models run
faster, fit in less GPU memory, and stop confidently making things up. The part I care
about is the one most people skip: not *that* something works, but *why* - which is how a
person ends up rebuilding GPT-2 from scratch on weekends.

The longer version streams token by token at
**[cris96spa-latent-space.com](https://www.cris96spa-latent-space.com/)**, a site that
animates a real GPT-2 forward pass because a PDF resume cannot do inference.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="dist/github-snake-dark.svg">
  <img alt="A snake eating this year's contribution graph, one commit at a time" src="dist/github-snake.svg">
</picture>

## Model card

| field | value |
| --- | --- |
| `base_model` | decoder-only human, one attention head |
| `pretraining` | MSc in Computer Science & Engineering, Politecnico di Milano, cum laude |
| `fine_tuning` | production LLMs at Artificialy - quantization and inference runtimes (vLLM, TensorRT), SFT / DPO / GRPO, evaluation pipelines |
| `objective` | training-loss curves going down. I could watch them for the rest of my life |
| `temperature` | 0 |
| `evals` | table football: SOTA. Dragon Ball: Sparking! Zero: ask Federico for a reference |
| `known_limitations` | red and green share an embedding. R is out of vocabulary |

## Checkpoints

| repo | what it is |
| --- | --- |
| [latent-space](https://github.com/cris96spa/latent-space) | My site. Animates a real GPT-2 forward pass and streams my bio token by token. |
| [LLMs-from-scratch](https://github.com/cris96spa/LLMs-from-scratch) | GPT-2 rebuilt from the tensor up - tokenizer, attention, training loop. Knowing *why* beats knowing *that*. |
| [fyt](https://github.com/cris96spa/fyt) | My girlfriend was running her thesis experiments in R. I hate R. The deal: she stops, I build her the framework. Here it is. |
| [teleportMPD](https://github.com/cris96spa/teleportMPD) | Master's thesis: Teleport MDPs, a formal account of why curricula work in RL where sparse rewards leave vanilla PPO wandering. |
| [hackapizza](https://github.com/cris96spa/hackapizza) | 2nd place at Hackapizza 2025: a RAG agent that turns Galactic Federation food law into a knowledge graph, so nobody orders the illegal pizza. |
| [LeetCode](https://github.com/cris96spa/LeetCode) | NeetCode 250 in Python, with a progress table kept honest by a script, not by vibes. |

The rest lives in the repositories tab; the
[projects page](https://www.cris96spa-latent-space.com/projects) has the director's cut.

## Config

```yaml
stack:
  daily:    [python, pytorch, fastapi, pydantic, polars, uv, ruff]
  llm:      [transformers, vllm, tensorrt, langgraph, mlflow]
  infra:    [docker, gcp, aws, github-actions]
  frontend: [react, typescript]  # Claude wrote it. My CSS loss never converged
  r:        null                 # see fyt
```

<p align="center">
  <a href="https://www.cris96spa-latent-space.com/">latent space</a> ·
  <a href="https://www.linkedin.com/in/cristian-c-spagnuolo/">LinkedIn</a> ·
  <a href="mailto:cristian.c.spagnuolo@gmail.com">email</a> ·
  <a href="https://www.cris96spa-latent-space.com/Cristian_C_Spagnuolo_CV.pdf">resume</a>
</p>

<p align="center"><i>Written at temperature 0.</i></p>
