# Towards a Comprehensive Taxonomy and Large-Scale Annotated Corpus for Online Slur Usage

Corpus repository for Jana Kurrek, Haji Mohammad Saleem, and Derek Ruths; 2020; "Towards a Comprehensive Taxonomy and Large-Scale Annotated Corpus for Online Slur Usage" at ALW | EMNLP. You can read it [here](https://www.aclweb.org/anthology/2020.alw-1.17.pdf).

**CONTENT WARNING: This corpus contains content that is racist, tarnsphobic, homophobic, and offensive in many other ways. Please use responsibly.**

## Comment Annotation Metadata

| FIELD        | INFO                                                                                            |
|--------------|-------------------------------------------------------------------------------------------------|
| id           | STR. ID to the Reddit comment.                                                                  |
| link_id      | STR. ID to the Reddit post the comment was made in.                                             |
| parent_id    | STR. ID to parent. Prefix `t1_` if the parent is another comment. Prefix `t3_` if it is a post. |
| score        | INT. Score the comment received.                                                                |
| subreddit    | STR. Subreddit the comment was made.                                                            |
| author       | STR. The author of the comment.                                                                 |
| slur         | STR. Slur in the comment.                                                                       |
| body         | STR. Body of the comment.                                                                       |
| disagreement | BOOLEAN. `True` if the two annotators did not agree on the label.                               |
| gold_label   | STR. Final label for the comment.                                                               |

## Comment Annotation Labels

| LABEL | INFO                             |
|-------|----------------------------------|
| DEG   | Derogatory                       |
| NDG   | Non Derogatory Non Appropriative |
| HOM   | Homonym                          |
| APR   | Appropriative                    |
| CMP   | Noise                            |

## Citation Information
*Please cite our paper in any published work that uses this resource.*
```
@inproceedings{kurrek-etal-2020-towards,
    title = "Towards a Comprehensive Taxonomy and Large-Scale Annotated Corpus for Online Slur Usage",
    author = "Kurrek, Jana  and
      Saleem, Haji Mohammad  and
      Ruths, Derek",
    booktitle = "Proceedings of the Fourth Workshop on Online Abuse and Harms",
    month = nov,
    year = "2020",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/2020.alw-1.17",
    doi = "10.18653/v1/2020.alw-1.17",
    pages = "138--149",
}
```
