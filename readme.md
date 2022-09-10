# JobBERT evaluation dataset :floppy_disk:

> [JobBERT publication](https://arxiv.org/abs/2109.09605)

This is the official repository containing the evaluation data that was used for the JobBERT paper. This dataset is a list of vacancy titles, each tagged with an <cite>[ESCO][1]</cite> occupation. The full dataset is split into two files in a stratified way by class distribution. The `titles.csv` file was used for validation during training, while the `titles.test.csv` file was used to determine the final performance of the trained models. 

:information_source: This data was automatically collected from a large <cite>[governmental job board][2]</cite>.

[1]: https://ec.europa.eu/esco/portal/occupation
[2]: https://www.myfuturejobs.gov.my/

## BibTeX Citation

If you use this dataset in a scientific publication, we would appreciate using the following citation:

```
@inproceedings{8720079,
  author       = {{Decorte, Jens-Joris and Van Hautte, Jeroen and Demeester, Thomas and Develder, Chris}},
  booktitle    = {{FEAST, ECML-PKDD 2021 Workshop, Proceedings}},
  language     = {{eng}},
  location     = {{Online}},
  pages        = {{9}},
  title        = {{JobBERT : understanding job titles through skills}},
  url          = {{https://feast-ecmlpkdd.github.io/papers/FEAST2021_paper_6.pdf}},
  year         = {{2021}},
}
```
