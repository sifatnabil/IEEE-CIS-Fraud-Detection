## IEEE-CIS Fraud Detection
This was a Kaggle competition organized by IEEE Computational Intelligence Society (IEEE-CIS) on Credit Card Fraud Detection. The dataset was provided by Vesta corporations. </br>
</br>
[Competition Link](https://www.kaggle.com/c/ieee-fraud-detection)

### Dependencies
- Pandas, [Installation Guide](https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html)
- LightGBM, [Installation Guide](https://lightgbm.readthedocs.io/en/latest/Installation-Guide.html)

### Load the trained model and run inference
```python
import lightgbm as lgb

lgbm_classifier = lgb.Booster(model_file="model.json")
output = lgbm_classifier.predict(test_data)
```
### Author
**Name:** Sifat Ul Alam </br>
**Email:** sifatnabil@gmail.com </br>
[LinkedIn](https://www.linkedin.com/in/sifat-nabil-2a9b3078/) ||
[GitHub](https://github.com/sifatnabil)

### Acknowledgments
- This repository was submitted as a project for Upskill's ISA IM Workshop.