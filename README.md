# CHR2024_prompt-and-image-dataset

## Dataset
This repository contains the data used for the paper "Bringing Rome to Life: Evaluating Historical Image Generation" by Phillip B. Ströbel, Zejie Guo, Ülkü Karagöz, Eva Maria Willi and Felix K. Maier at the [Computational Humanities Research 2024](https://2024.computational-humanities-research.org/) conference in Aarhus (December 4 to December 6). We will also include the results mentioned in the paper (see [here](https://2024.computational-humanities-research.org/papers/paper58/)).

### Structure

  - prompts_full.json
    The prompt file `prompts_full.json` contains 100 prompts we came up with by studying 20 research papers (15 about the triumphal procession, five about the Lupercalia). For each paper, we thought about five prompts. We used each prompt to generate six image versions.
  - ./images
    This folder contains all 600 images in `.png` format. The filename consists of [author_name]_p[n]_i[m].png, author_name being the name of the author from whose article we devised the prompt, n being the n-th prompt (1-5), and m being the m-th image version. Please see the paper for a list of papers we used to come up with the prompts.
  - vqa-resulst.json
    #TODO: add VQA results for the 600 images.

Please contact [Phillip B. Ströbel](mailto:phillip.stroebel@hist.uzh.ch) for questions.

If you want to use this data, please cite:
```
@inproceedings{stroebel2024bringing,
  title={{Bringing Rome to Life: Evaluating Historical Image Generation}},
  author={Str{\"o}bel, Phillip B and Guo, Zejie and Karag{\"o}z, {\"U}lk{\"u} and Willi, Eva Maria and Maier, Felix K},
  booktitle={Proceedings of the Computational Humanities Research Conference 2024},
  pages={113--126},
  year={2024},
  url={https://ceur-ws.org/Vol-3834/paper58.pdf}
}
```
