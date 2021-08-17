# JobBERT evaluation dataset :floppy_disk:.

This is the official repository containing the evaluation data that was used for the JobBERT paper. This dataset is a list of vacancy titles, each tagged with an <cite>[ESCO][1]</cite> occupation. The full dataset is split into two files in a stratified way by class distribution. The `titles.csv` file was used for validation during training, while the `titles.test.csv` file was used to determine the final performance of the trained models. 

:information_source: This data was automatically collected from a large <cite>[governmental job board][2]</cite>.

[1]: https://ec.europa.eu/esco/portal/occupation
[2]: https://www.myfuturejobs.gov.my/
