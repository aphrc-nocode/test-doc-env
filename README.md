## Test and Documentation
Repo for documentation and testing codebase for no-code platform with omop cdm

One project the repo includes is advanced feature selection. Feature selection is a critical step in machine learning to improve model performance, reduce overfitting, and enhance interpretability. The advanced feature selection project extracts candidate predictors from omop and submits the candidates to one or more feature selection methods like the fisher score and forward selection. Fisher score is a filter method that ranks features based on the ratio of between-class variance to within-class variance. Forward selection is a so-called "wrapper method" that starts with no features and adds one feature at a time that improves model performance. See [here]() for a landscape analysis of feature selection methods

## File system

- [docs](./docs): Should contain all the documents and write-ups. Some of these can be linked from the [README](./README.md)
- [data](./data): Should contain any data used to test concepts, ideas or codes
- [codes](./codes): Should contain all the codes developed to implement and idea, concept or examples, etc

## Other Repos
- [No-code app](https://github.com/aphrc-nocode/no-code-app)
- [Back-end R package](https://github.com/aphrc-nocode/Rautoml)
- [Docker containers](https://github.com/aphrc-nocode/no-code-devops)

