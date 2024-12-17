# Understanding Code Understandability Improvements in Code Reviews

This repository contains the CODE-UP (Code Understandability Improvement Dataset) and the artifacts of the findings by evaluate this dataset.

See [Understanding Code Understandability Improvements in Code Reviews](http://arxiv.org/pdf/2410.21990) (Delano Oliveira, Reydne Santos, Benedito de Oliveira, Martin Monperrus, Fernando Castor and Fernanda Madeiral), In IEEE Transactions on Software Engineering, 2024.

```bibtex
@article{2410.21990,
 title = {Understanding Code Understandability Improvements in Code Reviews},
 journal = {IEEE Transactions on Software Engineering},
 year = {2024},
 doi = {10.1109/tse.2024.3453783},
 author = {Delano Oliveira and Reydne Santos and Benedito de Oliveira and Martin Monperrus and Fernando Castor and Fernanda Madeiral},
 url = {http://arxiv.org/pdf/2410.21990},
}
```

List of selected projects: [projects.md](projects.md)

The full data is available here: [dataset.tsv](csv/dataset.tsv)

### Data by Research Questions

[RQ1. How often do reviewers ask for code understandability improvements in code review comments?](RQ1.md)

* [A classification of comments related to understandability, distinguishing between implicit and explicit comments. Additionally, a description of why each code review comment relates to understanding.](RQ1_subsample.md)

[RQ2. What are the main issues pertaining to code understandability in code review?](RQ2.md)

[RQ3. How likely are understandability improvement comments to be accepted?](RQ3.md)

[RQ4. What code changes are found in understandability improvements?](RQ4.md)

[RQ5. To what extent are accepted code understandability improvements reverted?](RQ5.md)

[RQ6. Can linters detect the identified code understandability smells?](RQ6.md)
