# Investigating the Emotional Experiences in eSports Spectatorship: the Case of League of Legends

This GitHub repository contains the data and source code related to the paper _"Investigating the Emotional Experiences in eSports Spectatorship: the Case of League of Legends"_ by Francesco Cauteruccio and Yubo Kou (Information Processing & Management, 60(3), 2023).

For any further information, feel free to reach out to us via email (Francesco Cauteruccio, [f.cauteruccio@staff.univpm.it](mailto:f.cauteruccio@staff.unvipm.it)).

## Data

The dataset is represented by a Comma Separate Values (.csv) file, which is available in the directory `data`. The symbol `;` is used as the columns separator. Each row of the file is a comment. The columns are:

- `id`: the unique identifier of the comment,
- `author`: the author who posted the comment (note that authors have been anonymized),
- `parent_id`: the parent element of the comment,
- `score`: the score of the comment,
- `body`: the textual content of the comment,
- `created`: the timestamp of creation of the comment,
- `pol_cmp`: the compound score assigned to the comment,
- `cflairs`: the list of the flairs carried by the author of the comment.

## Source code

The workflow of the computational analysis has been implemented in a Jupyter notebook using the Python programming language (version 3.8). The notebook file is `notebook/workflow.ipynb`.

## Reference

If you use or refer to this data in a paper, please consider citing the related paper:

```bibtex
@article{cauteruccio2023investigating,
    title={Investigating the emotional experiences in eSports spectatorship: The case of League of Legends},
    author={Cauteruccio, Francesco and Kou, Yubo},
    journal={Information Processing \& Management},
    volume={60},
    number={6},
    pages={103516},
    year={2023},
    publisher={Elsevier}
}
``