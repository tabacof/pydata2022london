## PyData 2022 London: Unlocking the power of gradient-boosted trees (using LightGBM)

**Abstract**: Gradient-boosted trees (XGBoost, LightGBM, Catboost) have become the staple of machine learning for tabular datasets. While most data scientists have made use of them at some point, many don’t know the true power those Python libraries provide. I will take LightGBM as an example and show in practice how it handles missing value imputation and categorical encoding natively, the different loss functions it provides for different problems (including the creation of your own loss function!), and how to interpret the resulting models. My aim is to show how LightGBM is like a Swiss army knife for machine learning and why it is the most pragmatic choice for tabular problems.

**Video**: https://www.youtube.com/watch?v=qGsHlvE8KZM

**Slides**: https://github.com/tabacof/pydata2022london/blob/main/PyData%20London%202022%20-%20LightGBM%20House%20Prices%20Example.ipynb

**Notebook**: https://github.com/tabacof/pydata2022london/blob/main/PyData%20London%202022_%20Unlocking%20the%20power%20of%20LightGBM%20(summarized).pdf

### Summary

This presentation is aimed at data science practitioners who deal with tabular (structured) datasets. Any company with a database will have a tabular dataset. Tabular problems include classification (e.g. predict fraud) and regression (e.g. predict revenue). Since the release of the XGBoost library, gradient-boosted trees (GBT) have dominated such problems in competitions like Kaggle when faced against any other machine learning model one-on-one. LightGBM is a newer and generally more efficient implementation of GBT algorithms.

While most practitioners will have heard and perhaps used such GBT models, many don’t know all the awesome features the modern libraries provide. This presentation aims to cover the most relevant features, explain them conceptually (e.g. how missing value imputation works behind the scene) and how to use them in practice (e.g. how to define your own custom loss function in Python). With this knowledge, you will be able to face any tabular dataset without having to resort to data cleaning tricks and deliver a performant model faster than any alternative (e.g. by using Scikit-learn, PyTorch or Tensorflow).

Here are the topics to be covered:

* Brief summary of the GBT algorithm: why is it better for tabular problems than linear or neural models?
* Missing value imputation: why not just use mean / median / mode imputation?
* Categorical encoding: why is it more convenient and performant than one-hot or label encoding?
* The loss function menu: which objective should you use for which problem?
* Custom loss functions: how to do it and why should you care?
* Model interpretability: how to use SHAP and why it is better than the default method?
* Pitfalls and takeaways: what can go wrong and what should you do next?
* Q&A

The presentation will be accompanied by a notebook that will allow reproducibility and code sharing.

