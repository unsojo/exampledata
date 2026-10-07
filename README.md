---
pretty_name: Rotten Tomatoes Movie Review Sentences (demo copy)
license: unknown
language:
  - en
task_categories:
  - text-classification
source: http://www.cs.cornell.edu/people/pabo/movie-review-data/
features:
  text: string
  label:
    class_label: [neg, pos]
---

# Rotten Tomatoes Movie Review Sentences

Short sentences taken from Rotten Tomatoes movie reviews, each labeled
**neg** (0, negative) or **pos** (1, positive). The data is balanced:
5,331 positive and 5,331 negative sentences, split into train
(8,530), validation (1,066) and test (1,066).

> **Demo copy.** This repository is a test copy used to build
> [Project Clover](https://projectclover.org/datasets). It is **not** an
> official upload by the original authors or by Cornell University.
> The original license is unknown; all credit belongs to the authors below.

## Files

| File | Rows |
|------|-----:|
| `data/train.csv` | 8,530 |
| `data/validation.csv` | 1,066 |
| `data/test.csv` | 1,066 |

Each file has two columns:

- `text`: the review sentence
- `label`: `0` = neg, `1` = pos

## Original source

Bo Pang and Lillian Lee, Cornell University.
Homepage: http://www.cs.cornell.edu/people/pabo/movie-review-data/
Paper: https://arxiv.org/abs/cs/0506075

## Citation

```bibtex
@InProceedings{Pang+Lee:05a,
  author    = {Bo Pang and Lillian Lee},
  title     = {Seeing stars: Exploiting class relationships for sentiment
               categorization with respect to rating scales},
  booktitle = {Proceedings of the ACL},
  year      = 2005
}
```
