<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="docs/brand/svg/forest-fires-logo-on-dark.svg">
    <img src="docs/brand/svg/forest-fires-logo-on-light.svg" alt="Forest Fires Prediction" width="320">
  </picture>
</p>

<h1 align="center">One notebook. From fire weather to burned area.</h1>

<p align="center">
  Coursework from 2020: machine learning on the UCI Forest Fires dataset.<br>
  <b>Regression first, then five burn-size classes.</b>
</p>

<p align="center">
  <a href="LICENSE"><img alt="License: MIT" src="https://img.shields.io/badge/license-MIT-3b82f6?style=flat-square"></a>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img alt="scikit-learn" src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white">
  <img alt="Jupyter" src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white">
  <img alt="Dataset: UCI Forest Fires" src="https://img.shields.io/badge/dataset-UCI%20Forest%20Fires-B4492F?style=flat-square">
  <a href="https://github.com/mertkayacs/Forestfires-Prediction-with-Machine-Learning"><img alt="GitHub stars" src="https://img.shields.io/github/stars/mertkayacs/Forestfires-Prediction-with-Machine-Learning?style=flat-square&logo=github&color=8A6D3B"></a>
</p>

<p align="center">
  <a href="https://colab.research.google.com/github/mertkayacs/Forestfires-Prediction-with-Machine-Learning/blob/master/Forestfires_prediction_with_Machine_Learning.ipynb"><img alt="Open in Colab" src="https://img.shields.io/badge/Open%20in%20Colab-B4492F?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjI0IiBoZWlnaHQ9IjI0Ij48ZyBmaWxsPSJub25lIiBzdHJva2U9IiNmZmZmZmYiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCIgc3Ryb2tlLXdpZHRoPSIyIj48cGF0aCBkPSJNMiA2aDQiLz48cGF0aCBkPSJNMiAxMGg0Ii8%2BPHBhdGggZD0iTTIgMTRoNCIvPjxwYXRoIGQ9Ik0yIDE4aDQiLz48cmVjdCB3aWR0aD0iMTYiIGhlaWdodD0iMjAiIHg9IjQiIHk9IjIiIHJ4PSIyIi8%2BPHBhdGggZD0iTTE2IDJ2MjAiLz48L2c%2BPC9zdmc%2B&logoColor=white"></a>
  <a href="Forestfire%20Prediction%20Paper%20by%20Mert%20KAYA.pdf"><img alt="Paper" src="https://img.shields.io/badge/Paper-1E2A38?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjI0IiBoZWlnaHQ9IjI0Ij48ZyBmaWxsPSJub25lIiBzdHJva2U9IiNmZmZmZmYiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCIgc3Ryb2tlLXdpZHRoPSIyIj48cGF0aCBkPSJNNiAyMmEyIDIgMCAwIDEtMi0yVjRhMiAyIDAgMCAxIDItMmg4YTIuNCAyLjQgMCAwIDEgMS43MDQuNzA2bDMuNTg4IDMuNTg4QTIuNCAyLjQgMCAwIDEgMjAgOHYxMmEyIDIgMCAwIDEtMiAyeiIvPjxwYXRoIGQ9Ik0xNCAydjVhMSAxIDAgMCAwIDEgMWg1Ii8%2BPHBhdGggZD0iTTEwIDlIOCIvPjxwYXRoIGQ9Ik0xNiAxM0g4Ii8%2BPHBhdGggZD0iTTE2IDE3SDgiLz48L2c%2BPC9zdmc%2B&logoColor=white"></a>
  <a href="#quick-start"><img alt="Quick start" src="https://img.shields.io/badge/Quick%20start-1E2A38?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjI0IiBoZWlnaHQ9IjI0Ij48ZyBmaWxsPSJub25lIiBzdHJva2U9IiNmZmZmZmYiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCIgc3Ryb2tlLXdpZHRoPSIyIj48cGF0aCBkPSJNMTIgMTV2NXMzLjAzLS41NSA0LTJjMS4wOC0xLjYyIDAtNSAwLTUiLz48cGF0aCBkPSJNNC41IDE2LjVjLTEuNSAxLjI2LTIgNS0yIDVzMy43NC0uNSA1LTJjLjcxLS44NC43LTIuMTMtLjA5LTIuOTFhMi4xOCAyLjE4IDAgMCAwLTIuOTEtLjA5Ii8%2BPHBhdGggZD0iTTkgMTJhMjIgMjIgMCAwIDEgMi0zLjk1QTEyLjg4IDEyLjg4IDAgMCAxIDIyIDJjMCAyLjcyLS43OCA3LjUtNiAxMWEyMi40IDIyLjQgMCAwIDEtNCAyeiIvPjxwYXRoIGQ9Ik05IDEySDRzLjU1LTMuMDMgMi00YzEuNjItMS4wOCA1IC4wNSA1IC4wNSIvPjwvZz48L3N2Zz4%3D&logoColor=white"></a>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="docs/assets/readme/hero-dark.webp">
    <img src="docs/assets/readme/hero-light.webp" alt="Notebook code that cross-validates KNN, SVM, MLP and Gaussian process classifiers" width="960">
  </picture>
</p>

Forest Fires Prediction is a single Jupyter notebook that studies the UCI Forest Fires dataset (Cortez and Morais, 2007). It first predicts the burned area as a regression problem, then turns the area into five classes from very low to very high and compares several classifiers. The notebook was written for Google Colab and includes forms where you enter weather values and read the predicted class. A short paper in Turkish describes the results.

---

## Why Forest Fires Prediction

The notebook walks through the problem from both directions.

|  |  |
|---|---|
| <img src="docs/assets/readme/icons/chart-scatter.svg" width="18" height="18" alt=""> **Regression, then classes** | Ordinary least squares, Ridge, Lasso and a KNN regressor predict the area. Most rows have an area of zero or close to it, so the notebook then groups the target into five classes. |
| <img src="docs/assets/readme/icons/sliders-horizontal.svg" width="18" height="18" alt=""> **Classes from K-Means** | K-Means centroids and fuzzy membership values produce the five labels. KNN, SVM with linear and polynomial kernels, logistic regression, an MLP and a Gaussian process classifier are compared. |
| <img src="docs/assets/readme/icons/notebook-text.svg" width="18" height="18" alt=""> **Forms you can try** | Colab form fields take month, day, temperature, humidity, wind and rain, and optionally grid coordinates and FWI values, and print the predicted class. |
| <img src="docs/assets/readme/icons/file-text.svg" width="18" height="18" alt=""> **A paper in Turkish** | The repository includes a paper that reports a best 5-fold cross-validation accuracy of 61.32 percent, from an SVM on month, weekday, temperature, humidity and wind. |

## A quick tour

<table>
  <tr>
    <td width="50%" valign="top">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="docs/assets/readme/tour/data-dark.webp">
        <img src="docs/assets/readme/tour/data-light.webp" alt="Saved notebook output showing the first five rows of the forest fires dataset">
      </picture>
      <h3>Dataset sample</h3>
      The first five rows of the UCI data as the notebook printed them, with grid coordinates, month, fire weather indices, weather and burned area.
    </td>
    <td width="50%" valign="top">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="docs/assets/readme/tour/results-dark.webp">
        <img src="docs/assets/readme/tour/results-light.webp" alt="Saved notebook output with three K-Means accuracy lines and the predicted classes of five models">
      </picture>
      <h3>Saved results</h3>
      The notebook keeps its printed K-Means accuracies for 5, 10 and 100 clusters and the class each model predicted for an example input.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="docs/assets/readme/tour/kmeans-dark.webp">
        <img src="docs/assets/readme/tour/kmeans-light.webp" alt="Code card of the K-Means and logistic regression cells of the notebook">
      </picture>
      <h3>K-Means labels</h3>
      K-Means with five clusters labels the area, and logistic regression is scored for 5, 10 and 100 clusters.
    </td>
    <td width="50%" valign="top">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="docs/assets/readme/tour/models-dark.webp">
        <img src="docs/assets/readme/tour/models-light.webp" alt="Code card of the classifier cross-validation cells of the notebook">
      </picture>
      <h3>Classifier comparison</h3>
      KNN, two SVMs, an MLP and a Gaussian process classifier are cross-validated on the same labels.
    </td>
  </tr>
</table>

<p align="center"><sub>The terminal cards show the outputs saved in the notebook, and the code cards show its cells as they are in the repository. Nothing was re-run.</sub></p>

## Features

**Regression**

- Ordinary least squares, Ridge, Lasso and KNN, scored by MSE.
- Residual plot to check linearity.

**Classification**

- Five classes from K-Means centroids with fuzzy labels.
- Three feature sets: weather and calendar, plus grid coordinates, plus FWI indices.

## Quick start

Open the notebook in Google Colab with the button above and run all cells. The dataset downloads from the UCI archive at run time, so no data files are needed. To run it locally:

```sh
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
jupyter notebook Forestfires_prediction_with_Machine_Learning.ipynb
```

Skip the google.colab Drive mount cell and the #@param form cells when running locally. The forms render only in Colab.

### Requirements

- Python 3 with the packages above, or a Google Colab session.

## FAQ

<details>
<summary><b>Where does the data come from?</b></summary>

The UCI Forest Fires dataset (Cortez and Morais, 2007), downloaded when the notebook runs.
</details>

<details>
<summary><b>Why classes instead of the exact area?</b></summary>

Most rows have an area at or near zero, which keeps the regression error high. The notebook groups the area into five classes with K-Means and fuzzy labels.
</details>

<details>
<summary><b>Do I need Colab?</b></summary>

The prediction forms need Colab. The analysis cells run locally.
</details>

<details>
<summary><b>Is there a write-up?</b></summary>

Yes. The paper in Turkish is in the repository as a PDF.
</details>

If Forest Fires Prediction is useful to you, a ⭐ helps other people find it.

## License

[MIT License](LICENSE). Photos behind the screenshots are credited in [docs/assets/readme/CREDITS.md](docs/assets/readme/CREDITS.md).

[![views](https://hits.sh/github.com/mertkayacs/Forestfires-Prediction-with-Machine-Learning.svg?view=today-total&style=flat-square&label=views&color=B4492F&labelColor=1E2A38)](https://github.com/mertkayacs/Forestfires-Prediction-with-Machine-Learning)
