# Self-adaptive stacking ensemble

* Self-adaptive stacking ensemble using genetic algorithm for imbalanced semi-supervised learning.

* Required Python 3 packages: 
    1. sklearn (https://github.com/scikit-learn/scikit-learn)
    2. imblearn (https://github.com/scikit-learn-contrib/imbalanced-learn)
    3. lightgbm (optional, https://github.com/microsoft/LightGBM)

* BESS is compatible with most sklearn APIs but is not strictly tested.

* Import: `from SASE import SelfAdaptiveStackingEnsemble`

* Train: `fit(X, y)`, with target `-1` as the unlabeled data, `0` as the majority class, and `1` as the minority class.

* Predict: `predict(X)` (hard predictions) or `predict_proba(X)` (soft predictions).
