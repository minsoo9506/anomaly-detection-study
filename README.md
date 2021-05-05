# Outlier Analysis (2017) - Charu C. Aggarwal
- Probabilistic and Statistical Models for Outlier Detection
  - `My Summary` | `My Code`
- Linear Models for Outlier Detection
  - `My Summary` | `My Code`
- Proximity-Based Outlier Detection
  - `My Summary` | `My Code`
- High-Dimensional Outlier Detection
  - `My Summary` | `My Code`
- Outlier Ensembles
  - `My Summary` | `My Code`
- Time Series and Streaming Outlier Detection
  - prediction-based anomaly detection
    - univariate case : [`My Code` (ARIMA)](./time%20series%20and%20streaming%20anomaly%20detection)
    - multiple time series : [`My Code`](./time%20series%20and%20streaming%20anomaly%20detection)
      - selection method
      - pca method

# Deep Anomaly Detection
- Categoriztion of deep anomaly detection
  - Deep learning for feature extraction
  - Learning feature representations of normality
    - Generic normality feature learning
      - autoencoder, gan, predictability modeling, self-supervised classification
    - Anomaly measure-dependent feature learning
      - distance-based classification, one-class classification measure, clustering-based measure
  - End-to-end anomaly score learning
    - ranking model, prior-driven model, softmax likelihood model, end-to-end one-class classification
### Survey
- Deep Learning for Anomaly Detection A Review (2020)
  - [`Paper Link`](https://arxiv.org/pdf/2007.02500.pdf) | [`My Summary`](summary) | `My Code`
  - `Key Word` : deep anomaly detection
- Autoencoders (2020)
  - [`Paper Link`](https://arxiv.org/pdf/2003.05991.pdf) | `My Summary` | `My Code`
  - `Key Word` : autoencoder

### Learning feature representations of normality
- Outlier Detection with AutoEncoder Ensemble (2017)
  - [`Paper Link`](https://saketsathe.net/downloads/autoencoder.pdf) | `My Summary` | `My Code`
  - `Key Word` : autoencoder, ensemble
- Auto-Encoding Variational Bayes (2014)
  - [`Paper Link`](https://arxiv.org/abs/1312.6114) | `My Summary` | [`My Code`](code)
  - `Key Word` : variational autoencoder
- Generatice Adversarial Nets (NIPS 2014)
  - [`Paper Link`](https://papers.nips.cc/paper/2014/hash/5ca3e9b122f61f8f06494c97b1afccf3-Abstract.html) | [`My Summary`](summary) | [`My Code`](Code)
  - `Key Word` : gan
- Adversarial Autoencoders (2016)
  - [`Paper Link`](https://arxiv.org/abs/1511.05644) | [`My Summary`](summary) | `My Code`
  - `Key Word` : autoencoder, adversarial, semi-sup, dim reduction
- Generative Probabilistic Novelty Detection with Adversarial Autoencoders (NIPS 2018)
  - [`Paper Link`](https://papers.nips.cc/paper/2018/file/5421e013565f7f1afa0cfe8ad87a99ab-Paper.pdf) | [`My Summary`] | [`My Code`]
- dfd
  - [`Paper Link`](https://sites.cs.ucsb.edu/~bzong/doc/iclr18-dagmm.pdf) | [`My Summary`] | [`My Code`]

# Time Series and Streaming Anomaly Detection
- Anomaly Detection In Univariate Time-Series : A Survey on the state-of-the-art
  - [`Paper Link`](https://arxiv.org/abs/2004.00433) | `My Summary` | `My Code`
  - `Key Word` : anomaly detection, time series
- USAD : UnSupervised Anomaly Detection on multivariate time series (KDD2020)
  - [`Paper Link`](https://dl.acm.org/doi/10.1145/3394486.3403392) | [`My Summary`] | [`My Code`]
  - `Key Word` : GAN, AE, multivariate time series

# Project
- Kaggle Credit Card Fraud Detection
  - tabular, binary classification, imbalance
  - 이론 적용
    - SMOTE
    - Unsupervised PCA based anomaly detection