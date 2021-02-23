# raskls
Richard's Auxiliary Sci-Kit Learn Stuff. Various homemade estimators that I use often enough that I wanted to wrap them all up.

### Contents:
  - Tranformers
    - ColumnAutoTransformer
      - _Hands-off preprocessor. Interprets features and performs transformations according to their type (numerical, categorical, etc.), with sensible defaults and easy tweaking._
    - DictEncoder (Comming Soon)
  - Optimizers
    - RandomSeedSearchCV
      - _Variation on RandomSearchCV. Enables easier searching across large or abnormal parameter spaces by calling a user-provided model-generating function to produce randomized models with only a random seed as input._
