# SentimentAnalysisSVM
[Sumber : https://medium.com/scrapehero/sentiment-analysis-using-svm-338d418e3ff1](https://medium.com/scrapehero/sentiment-analysis-using-svm-338d418e3ff1)

---

Dilakukan percobaan untuk membuat model SVM dengan kernel linear, dataset latih dan tes berasal dari [https://github.com/Vasistareddy/sentiment_analysis](https://github.com/Vasistareddy/sentiment_analysis).

Proses Vektorisasi kalimat menggunakan vectorizer dari library sklearn yaitu TfidVectorizer.

Berdasarkan hasil percobaan yang dilakukan dalam proses pembuatan model SVM untuk analisis sentimen, didapat:

- Positif
  - Precision   :  0.919
  - Recall      :  0.910
  - F-1 Score   :  0.914
  - Support     :  1.000

- Negatif
  - Precision   :  0.910
  - Recall      :  0.920
  - F-1 Score   :  0.915
  - Support     :  1.000


Dapat disimpulkan bahwa model SVM yang dibuat tidak mengalami overfitting maupun underfitting, dan tergeneralisasi dengan baik.
dibutuhkan lebih banyak data untuk memperkaya pengetahuan model serta *hyperparameter fine tuning* untuk bisa meningkatkan akurasi dari model.
