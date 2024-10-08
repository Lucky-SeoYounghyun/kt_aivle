# Summary of 1_Linear

[<< Go back](../README.md)


## Linear Regression (Linear)
- **n_jobs**: -1
- **explain_level**: 2

## Validation
 - **validation_type**: kfold
 - **k_folds**: 5
 - **shuffle**: True

## Optimized metric
rmse

## Training time

17.1 seconds

### Metric details:
| Metric   |        Score |
|:---------|-------------:|
| MAE      |   138.603    |
| MSE      | 47448.8      |
| RMSE     |   217.828    |
| R2       |     0.66778  |
| MAPE     |     0.593455 |



## Learning curves
![Learning curves](learning_curves.png)

## Coefficients
| feature        |    Learner_1 |    Learner_2 |    Learner_3 |    Learner_4 |    Learner_5 |
|:---------------|-------------:|-------------:|-------------:|-------------:|-------------:|
| 총세대수       |  2.87528     |  2.58621     |  4.53488     |  2.53031     |  2.19941     |
| 총면적         |  1.09865     |  0.766861    |  0.624335    |  1.35379     |  0.594609    |
| 면적127_139    |  0.230002    |  0.169954    | -0.0464899   |  0.198367    |  0.209993    |
| 준공연도       |  0.104204    |  0.115595    |  0.096875    |  0.0802714   |  0.0879127   |
| 임대보증금     |  0.104673    |  0.0746274   |  0.0789625   |  0.0413947   |  0.117986    |
| 난방방식       |  0.0641148   |  0.0543867   |  0.0564197   |  0.0937737   |  0.0829569   |
| 승강기설치여부 |  0.0623025   |  0.0939268   |  0.0781928   |  0.0583689   |  0.0320576   |
| intercept      |  8.69146e-16 |  9.79683e-16 |  1.22525e-16 | -6.64808e-16 | -2.45535e-17 |
| 건물형태       | -0.143913    | -0.16777     | -0.138842    | -0.166242    | -0.097393    |
| 임대료         | -0.204953    | -0.200127    | -0.195511    | -0.161258    | -0.142001    |
| 면적85_127     | -0.628732    | -0.450958    | -0.0464899   | -0.574068    | -0.427189    |
| 면적59_74      | -0.588292    | -0.793518    | -1.43829     | -0.892948    | -0.564279    |
| 면적74_85      | -1.00648     | -0.789598    | -1.12115     | -1.11662     | -0.625606    |
| 면적17_26      | -0.889406    | -0.97223     | -1.2928      | -0.916848    | -0.806401    |
| 면적46_51      | -1.12106     | -1.03756     | -1.80049     | -1.20082     | -0.799313    |
| 면적38_46      | -1.52103     | -1.11788     | -2.03203     | -1.30004     | -0.9353      |
| 면적26_38      | -1.43583     | -1.29548     | -2.32531     | -1.4468      | -1.00923     |
| 면적51_59      | -1.85588     | -1.43145     | -2.44932     | -1.72318     | -1.08919     |


## Permutation-based Importance
![Permutation-based Importance](permutation_importance.png)
## True vs Predicted

![True vs Predicted](true_vs_predicted.png)


## Predicted vs Residuals

![Predicted vs Residuals](predicted_vs_residuals.png)



## SHAP Importance
![SHAP Importance](shap_importance.png)

## SHAP Dependence plots

### Dependence (Fold 1)
![SHAP Dependence from Fold 1](learner_fold_0_shap_dependence.png)
### Dependence (Fold 2)
![SHAP Dependence from Fold 2](learner_fold_1_shap_dependence.png)
### Dependence (Fold 3)
![SHAP Dependence from Fold 3](learner_fold_2_shap_dependence.png)
### Dependence (Fold 4)
![SHAP Dependence from Fold 4](learner_fold_3_shap_dependence.png)
### Dependence (Fold 5)
![SHAP Dependence from Fold 5](learner_fold_4_shap_dependence.png)

## SHAP Decision plots

### Top-10 Worst decisions (Fold 1)
![SHAP worst decisions from fold 1](learner_fold_0_shap_worst_decisions.png)
### Top-10 Worst decisions (Fold 2)
![SHAP worst decisions from fold 2](learner_fold_1_shap_worst_decisions.png)
### Top-10 Worst decisions (Fold 3)
![SHAP worst decisions from fold 3](learner_fold_2_shap_worst_decisions.png)
### Top-10 Worst decisions (Fold 4)
![SHAP worst decisions from fold 4](learner_fold_3_shap_worst_decisions.png)
### Top-10 Worst decisions (Fold 5)
![SHAP worst decisions from fold 5](learner_fold_4_shap_worst_decisions.png)
### Top-10 Best decisions (Fold 1)
![SHAP best decisions from fold 1](learner_fold_0_shap_best_decisions.png)
### Top-10 Best decisions (Fold 2)
![SHAP best decisions from fold 2](learner_fold_1_shap_best_decisions.png)
### Top-10 Best decisions (Fold 3)
![SHAP best decisions from fold 3](learner_fold_2_shap_best_decisions.png)
### Top-10 Best decisions (Fold 4)
![SHAP best decisions from fold 4](learner_fold_3_shap_best_decisions.png)
### Top-10 Best decisions (Fold 5)
![SHAP best decisions from fold 5](learner_fold_4_shap_best_decisions.png)

[<< Go back](../README.md)
