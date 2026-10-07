# 📚 scikit-learn Cookbook

> **Tugas 2 — Machine Learning (Enrichment Class)**  
> **Code Reproduction + Theoretical Deep-Dive from *scikit-learn Cookbook***  
> Telkom University

---

## 👤 Identitas Mahasiswa

| Field | Detail |
|---|---|
| **Nama** | Satrio Arjuna Putra |
| **NIM** | 101032330178 |
| **Kelas** | TK-47-05 |
| **Mata Kuliah** | Machine Learning (Enrichment) |
| **Referensi Utama** | *scikit-learn Cookbook* (O'Reilly / Packt) |
| **Repository GitHub** | [SatrioArjunaPutra/scikit-learn-cookbook](https://github.com/SatrioArjunaPutra/scikit-learn-cookbook) |

---

## 📖 Ringkasan Repository

Repository ini berisi reproduksi kode lengkap (*code reproduction*), penjelasan teoretis mendalam (*theoretical deep-dive*), visualisasi interaktif, dan ringkasan terstruktur dari seluruh **13 Bab** buku *scikit-learn Cookbook*. Setiap bab dirancang sebagai modul mandiri (*self-contained notebook*) yang dapat dijalankan langsung di lingkungan lokal maupun **Google Colab**.

---

## 📑 Daftar Isi & Akses Notebook (Chapters 01 – 13)

| # | Bab / Topik | Notebook | Open in Colab | Topik Utama & Algoritma |
|:---:|:---|:---:|:---:|:---|
| **01** | **API Elements of scikit-learn** | [ch01_sklearn_api.ipynb](01.%20API%20Elements%20of%20scikit-learn/ch01_sklearn_api.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SatrioArjunaPutra/scikit-learn-cookbook/blob/main/01.%20API%20Elements%20of%20scikit-learn/ch01_sklearn_api.ipynb) | Estimator, Transformer, Predictor, Pipeline, ColumnTransformer, BaseEstimator/TransformerMixin |
| **02** | **Data Preprocessing** | [ch02_preprocessing.ipynb](02.%20Data%20Preprocessing/ch02_preprocessing.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SatrioArjunaPutra/scikit-learn-cookbook/blob/main/02.%20Data%20Preprocessing/ch02_preprocessing.ipynb) | StandardScaler, MinMaxScaler, RobustScaler, SimpleImputer, KNNImputer, OneHotEncoder, OrdinalEncoder, KBinsDiscretizer |
| **03** | **Dimensionality Reduction** | [Chapter_03_Dimensionality_Reduction.ipynb](03.%20Dimensionality%20Reduction/Chapter_03_Dimensionality_Reduction.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SatrioArjunaPutra/scikit-learn-cookbook/blob/main/03.%20Dimensionality%20Reduction/Chapter_03_Dimensionality_Reduction.ipynb) | Principal Component Analysis (PCA), Linear Discriminant Analysis (LDA), t-SNE, Explained Variance Ratio |
| **04** | **Distance Metrics & Nearest Neighbors** | [Chapter_04_Distance_Metrics_KNN.ipynb](04.%20Models%20with%20Distance%20Metrics%20and%20Nearest%20Neighbors/Chapter_04_Distance_Metrics_KNN.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SatrioArjunaPutra/scikit-learn-cookbook/blob/main/04.%20Models%20with%20Distance%20Metrics%20and%20Nearest%20Neighbors/Chapter_04_Distance_Metrics_KNN.ipynb) | KNeighborsClassifier, KNeighborsRegressor, Metrik Jarak (Euclidean, Manhattan, Minkowski, Cosine), KD-Tree & Ball-Tree |
| **05** | **Linear Models and Regularization** | [Chapter_05_Linear_Models_Regularization.ipynb](05.%20Linear%20Models%20and%20Regularization/Chapter_05_Linear_Models_Regularization.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SatrioArjunaPutra/scikit-learn-cookbook/blob/main/05.%20Linear%20Models%20and%20Regularization/Chapter_05_Linear_Models_Regularization.ipynb) | OLS Linear Regression, Ridge ($L_2$), Lasso ($L_1$), ElasticNet, SplineTransformer, Polynomial Features |
| **06** | **Advanced Logistic Regression** | [Chapter_06_Logistic_Regression.ipynb](06.%20Advanced%20Logistic%20Regression/Chapter_06_Logistic_Regression.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SatrioArjunaPutra/scikit-learn-cookbook/blob/main/06.%20Advanced%20Logistic%20Regression/Chapter_06_Logistic_Regression.ipynb) | Logistic Regression Binary & Multinomial, OvR / Softmax, Regularization Paths, Class Imbalance, ROC-AUC Curve |
| **07** | **Support Vector Machines & Kernel Methods** | [Chapter_07_SVM_Kernel_Methods.ipynb](07.%20Support%20Vector%20Machines%20and%20Kernel%20Methods/Chapter_07_SVM_Kernel_Methods.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SatrioArjunaPutra/scikit-learn-cookbook/blob/main/07.%20Support%20Vector%20Machines%20and%20Kernel%20Methods/Chapter_07_SVM_Kernel_Methods.ipynb) | SVC, SVR, LinearSVC, Kernel Trick (Linear, Polynomial, RBF, Sigmoid), Margin Maximization, Slack Variables ($C$), Gamma ($\gamma$) |
| **08** | **Tree-Based Algorithms & Ensemble Methods** | [ch8_tree_based_algorithms.ipynb](08.%20Tree-Based%20Algorithms%20and%20Ensemble%20Methods/ch8_tree_based_algorithms.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SatrioArjunaPutra/scikit-learn-cookbook/blob/main/08.%20Tree-Based%20Algorithms%20and%20Ensemble%20Methods/ch8_tree_based_algorithms.ipynb) | DecisionTreeClassifier, Random Forest, AdaBoost, GradientBoostingClassifier, Feature Importance, Bagging vs Boosting |
| **09** | **Text Processing & Multiclass Classification** | [Ch9_Text_Processing_and_Multiclass_Classification.ipynb](09.%20Text%20Processing%20and%20Multiclass%20Classification/Ch9_Text_Processing_and_Multiclass_Classification.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SatrioArjunaPutra/scikit-learn-cookbook/blob/main/09.%20Text%20Processing%20and%20Multiclass%20Classification/Ch9_Text_Processing_and_Multiclass_Classification.ipynb) | CountVectorizer, TfidfVectorizer, NLTK Tokenization & Stopwords, MultinomialNB, OneVsRestClassifier, Multi-label Binarizer |
| **10** | **Clustering Techniques** | [Ch10_Clustering_Techniques.ipynb](10.%20Clustering%20Techniques/Ch10_Clustering_Techniques.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SatrioArjunaPutra/scikit-learn-cookbook/blob/main/10.%20Clustering%20Techniques/Ch10_Clustering_Techniques.ipynb) | K-Means, K-Means++, Hierarchical Agglomerative Clustering, DBSCAN, Gaussian Mixture Models (GMM), Silhouette Score, Elbow Method |
| **11** | **Novelty and Outlier Detection** | [ch11_novelty_outlier_detection.ipynb](11.%20Novelty%20and%20Outlier%20Detection/ch11_novelty_outlier_detection.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SatrioArjunaPutra/scikit-learn-cookbook/blob/main/11.%20Novelty%20and%20Outlier%20Detection/ch11_novelty_outlier_detection.ipynb) | Isolation Forest, One-Class SVM, Local Outlier Factor (LOF), EllipticEnvelope (Mahalanobis distance), Outlier vs Novelty paradigm |
| **12** | **Cross-Validation & Model Evaluation** | [Ch12_Cross_Validation_and_Model_Evaluation.ipynb](12.%20Cross-Validation%20and%20Model%20Evaluation/Ch12_Cross_Validation_and_Model_Evaluation.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SatrioArjunaPutra/scikit-learn-cookbook/blob/main/12.%20Cross-Validation%20and%20Model%20Evaluation/Ch12_Cross_Validation_and_Model_Evaluation.ipynb) | K-Fold, StratifiedKFold, TimeSeriesSplit, GridSearchCV, RandomizedSearchCV, Learning Curves, Validation Curves, Metrik Presisi/Recall/F1 |
| **13** | **Deploying Models in Production** | [Ch13_Deploying_sklearn_Models_in_Production.ipynb](13.%20Deploying%20Models%20in%20Production/Ch13_Deploying_sklearn_Models_in_Production.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SatrioArjunaPutra/scikit-learn-cookbook/blob/main/13.%20Deploying%20Models%20in%20Production/Ch13_Deploying_sklearn_Models_in_Production.ipynb) | Model Serialization (`joblib`, `pickle`), Pipeline Serialization, API Schema Validation, Latency Benchmarking, Production Best Practices |

---

## 🔍 Ringkasan Mendalam Per Bab (*Theoretical Deep-Dive*)

### Bab 1: API Elements of scikit-learn
- **Filosofi Desain**: Konsistensi antarmuka objek berbasis konsep *Estimator* (`fit`), *Transformer* (`transform`, `fit_transform`), dan *Predictor* (`predict`, `predict_proba`).
- **Komposisi Pipeline**: Menggabungkan tahapan preprocessing dan model ke dalam satu objek terpadu (`Pipeline`), mencegah *data leakage* antar lipatan validasi silang.
- **Custom Components**: Pembuatan modul khusus turunan `BaseEstimator` dan `TransformerMixin` dengan kepatuhan penuh terhadap standar API scikit-learn.

### Bab 2: Data Preprocessing
- **Pembersihan & Transformasi Fitur**: Penanganan *missing values* melalui pendekatan statistik univariat (`SimpleImputer`) dan multivariat berbasis ketetanggaan (`KNNImputer`).
- **Penykalaan Numerik**: Analisis perbandingan sensitivitas terhadap outlier antara `StandardScaler` ($z = \frac{x - \mu}{\sigma}$), `MinMaxScaler` ($x' = \frac{x - x_{min}}{x_{max} - x_{min}}$), dan `RobustScaler` berbasis kuartil IQR.
- **Encoding Kategori & Diskritisasi**: Penerapan `OneHotEncoder` untuk nominal bebas urutan, `OrdinalEncoder` untuk data berurutan, serta `KBinsDiscretizer` untuk pemartisian variabel kontinu.

### Bab 3: Dimensionality Reduction
- **Principal Component Analysis (PCA)**: Metode tanpa pengawasan (*unsupervised*) yang memproyeksikan data ke arah varians maksimum melalui dekomposisi nilai eigen (*eigendecomposition*) atau SVD dari matriks kovariansi.
- **Linear Discriminant Analysis (LDA)**: Metode terbimbing (*supervised*) yang memaksimalkan rasio dispersi antarkelas (*between-class scatter*) terhadap dispersi dalam-kelas (*within-class scatter*).
- **Manifold Learning (t-SNE)**: Teknik reduksi non-linear berbasis probabilitas ketetanggaan untuk visualisasi data dimensi tinggi ke ruang 2D/3D.

### Bab 4: Models with Distance Metrics and Nearest Neighbors
- **Konsep K-Nearest Neighbors (KNN)**: Algoritma non-parametrik berbasis *instance-based learning* yang mengklasifikasikan titik baru berdasarkan mayoritas kelas $k$ tetangga terdekat.
- **Metrik Jarak**: Formulasi matematis jarak Euclidean ($L_2$), Manhattan ($L_1$), Minkowski ($L_p$), dan Cosine similarity.
- **Optimasi Struktur Data**: Pemanfaatan *KD-Tree* dan *Ball-Tree* untuk memangkas kompleksitas komputasi pencarian tetangga dari $O(N)$ menjadi $O(\log N)$.

### Bab 5: Linear Models and Regularization
- **Regresi Linear (OLS)**: Minimasi *Residual Sum of Squares* (RSS) $\min_\beta \|y - X\beta\|_2^2$.
- **Teknik Regularisasi**:
  - **Ridge ($L_2$)**: Penambahan penalti kuadrat $\|\beta\|_2^2$ untuk mengatasi multikolinearitas dan memperkecil varians bobot.
  - **Lasso ($L_1$)**: Penambahan penalti absolut $\|\beta\|_1$ yang mendorong kelangkaan parameter (*sparsity*) sebagai seleksi fitur alami.
  - **ElasticNet**: Kombinasi konveks penalti $L_1$ dan $L_2$.
- **Ekstensi Non-Linear**: `SplineTransformer` dan `PolynomialFeatures` untuk menangkap relasi non-linear menggunakan estimator linear.

### Bab 6: Advanced Logistic Regression
- **Klasifikasi Probabilistik**: Pemodelan odds logaritmik $\log\left(\frac{p}{1-p}\right) = X\beta$ dengan fungsi aktivasi Sigmoid $\sigma(z) = \frac{1}{1 + e^{-z}}$.
- **Multiclass Strategies**: Pendekatan *One-vs-Rest* (OvR) dan *Multinomial/Softmax* loss.
- **Penanganan Ketidakseimbangan Kelas**: Penyesuaian `class_weight='balanced'` dan penentuan ambang batas keputusan (*threshold tuning*) berdasarkan kurva ROC-AUC dan Precision-Recall.

### Bab 7: Support Vector Machines & Kernel Methods
- **Maksimasi Margin**: Menemukan *hyperplane* pemisah optimal dengan memaksimalkan jarak margin $\frac{2}{\|w\|}$, tunduk pada kendala margin keras (*hard margin*) maupun lunak (*soft margin* dengan parameter penalti $C$).
- **Kernel Trick**: Pemetaan implisit data berdimensi rendah ke ruang berdimensi tinggi via fungsi kernel tanpa menghitung koordinat secara eksplisit:
  - Kernel RBF/Gaussian: $K(x, x') = \exp(-\gamma \|x - x'\|^2)$
  - Kernel Polinomial: $K(x, x') = (\gamma \langle x, x' \rangle + r)^d$

### Bab 8: Tree-Based Algorithms and Ensemble Methods
- **Decision Trees**: Pemisahan simpul berdasarkan kriteria ketakmurnian Gini (*Gini Impurity*) atau Entropi (*Information Gain*), serta regulasi kedalaman (*pruning*).
- **Bagging (Random Forest)**: Pengurangan varians melalui rata-rata prediksi dari ratusan pohon acak yang dilatih dengan subsampling baris (*bootstrap*) dan subsampling fitur acak.
- **Boosting (AdaBoost & Gradient Boosting)**: Pengurangan bias secara sekuensial dengan melatih pohon-pohon dangkal (*weak learners*) untuk mengoreksi residual kesalahan model sebelumnya.

### Bab 9: Text Processing & Multiclass Classification
- **Vektorasi Teks**: Transformasi teks alami ke matriks frekuensi istilah (*Bag-of-Words* via `CountVectorizer`) dan penbobotan kepentingan kata berbasis `TfidfVectorizer` ($TF \times \log\frac{N}{DF}$).
- **Pra-pemrosesan Linguistik**: Tokenisasi, penghapusan *stopwords*, dan normalisasi lema menggunakan NLTK.
- **Model Klasifikasi Teks**: Naive Bayes Multinomial dan Linear Support Vector Classifier pada ruang fitur berdimensi tinggi dan renggang (*sparse*).

### Bab 10: Clustering Techniques
- **K-Means & K-Means++**: Partisi data ke dalam $k$ klaster dengan meminimalkan inersia (jarak kuadrat ke *centroid*), diinisialisasi secara probabilistik melalui K-Means++.
- **Hierarchical Agglomerative Clustering**: Pengelompokan hierarkis *bottom-up* dengan metrik keterkaitan *Ward*, *Complete*, dan *Average linkage*.
- **DBSCAN**: Klasterisasi berbasis kerapatan spasial yang mampu mendeteksi klaster bergeometri bebas sekaligus memisahkan *noise/outliers*.
- **Evaluasi Klaster**: Analisis Silhouette Coefficient dan Elbow Curve.

### Bab 11: Novelty and Outlier Detection
- **Distingsi Paradigma**: *Outlier Detection* (mendeteksi anomali dalam data pelatihan) vs *Novelty Detection* (mengidentifikasi apakah sampel baru tidak lazim dibanding data referensi bersih).
- **Metode Utama**:
  - **Isolation Forest**: Memisahkan anomali berdasarkan kedalaman pohon pemisah acak (anomali terisolasi lebih cepat di kedalaman dangkal).
  - **One-Class SVM**: Mempelajari batas batas pendukung ketat yang membungkus sebagian besar data normal.
  - **Local Outlier Factor (LOF)**: Mengukur deviasi densitas lokal sampel relatif terhadap densitas tetangga-tetangganya.

### Bab 12: Cross-Validation and Model Evaluation
- **Skema Validasi**: *K-Fold*, *Stratified K-Fold* (menjaga distribusi rasio kelas), dan *Time Series Split* (mencegah kebocoran masa depan).
- **Optimasi Hiperparameter**: Eksplorasi ruang parameter komprehensif via `GridSearchCV` dan pencarian stokastik efisien via `RandomizedSearchCV`.
- **Diagnostik Model**: *Learning Curves* untuk mendeteksi *underfitting/overfitting* serta *Validation Curves* untuk menganalisis sensitivitas parameter.

### Bab 13: Deploying Models in Production
- **Serialisasi Pipeline**: Penyimpanan artefak model dan rantai transformator menggunakan `joblib` berkinerja tinggi untuk array numerik besar.
- **Validasi Input**: Pengecekan skema tipe data, format array, dan keberadaan *missing values* sebelum inferensi.
- **Benchmarking & Latensi**: Pengukuran waktu inferensi per sampel dan *throughput batching* untuk persiapan integrasi REST API atau microservices.

---

## 🗂️ Struktur Direktori

```
scikit-learn-cookbook/
├── 01. API Elements of scikit-learn/
│   └── ch01_sklearn_api.ipynb
├── 02. Data Preprocessing/
│   └── ch02_preprocessing.ipynb
├── 03. Dimensionality Reduction/
│   └── Chapter_03_Dimensionality_Reduction.ipynb
├── 04. Models with Distance Metrics and Nearest Neighbors/
│   └── Chapter_04_Distance_Metrics_KNN.ipynb
├── 05. Linear Models and Regularization/
│   └── Chapter_05_Linear_Models_Regularization.ipynb
├── 06. Advanced Logistic Regression/
│   └── Chapter_06_Logistic_Regression.ipynb
├── 07. Support Vector Machines and Kernel Methods/
│   └── Chapter_07_SVM_Kernel_Methods.ipynb
├── 08. Tree-Based Algorithms and Ensemble Methods/
│   └── ch8_tree_based_algorithms.ipynb
├── 09. Text Processing and Multiclass Classification/
│   └── Ch9_Text_Processing_and_Multiclass_Classification.ipynb
├── 10. Clustering Techniques/
│   └── Ch10_Clustering_Techniques.ipynb
├── 11. Novelty and Outlier Detection/
│   └── ch11_novelty_outlier_detection.ipynb
├── 12. Cross-Validation and Model Evaluation/
│   └── Ch12_Cross_Validation_and_Model_Evaluation.ipynb
├── 13. Deploying Models in Production/
│   └── Ch13_Deploying_sklearn_Models_in_Production.ipynb
├── README.md
└── requirements.txt
```

---

## 🚀 Panduan Memulai (*Getting Started*)

### 1. Prasyarat Sistem
- Python 3.9+ (disarankan Python 3.10 atau 3.11)
- Lingkungan Jupyter Notebook / JupyterLab atau Google Colab

### 2. Kloning Repository
```bash
git clone https://github.com/SatrioArjunaPutra/scikit-learn-cookbook.git
cd scikit-learn-cookbook
```

### 3. Instalasi Dependensi
Disarankan menggunakan virtual environment:
```bash
# Membuat virtual environment
python -m venv venv

# Aktivasi virtual environment (Windows)
venv\Scripts\activate

# Aktivasi virtual environment (macOS/Linux)
# source venv/bin/activate

# Install semua paket yang dibutuhkan
pip install -r requirements.txt
```

### 4. Menjalankan Jupyter Notebook
```bash
jupyter notebook
```
Buka browser dan navigasikan ke folder bab yang diinginkan (misal `01. API Elements of scikit-learn/ch01_sklearn_api.ipynb`).

---

## 📦 Paket & Dependensi Utama

| Paket | Versi Minimum | Deskripsi / Fungsi |
|---|---|---|
| `scikit-learn` | $\ge 1.3.0$ | Algoritma ML, preprocessing, metrik evaluasi, pipeline |
| `numpy` | $\ge 1.24.0$ | Operasi aljabar linier dan komputasi array multidimensi |
| `pandas` | $\ge 2.0.0$ | Manipulasi, pembersihan, dan analisis data tabular |
| `matplotlib` | $\ge 3.7.0$ | Pembuatan grafik dan visualisasi data dasar |
| `seaborn` | $\ge 0.12.0$ | Visualisasi statistik interaktif berbasis Matplotlib |
| `scipy` | $\ge 1.11.0$ | Matriks renggang (*sparse matrix*) dan fungsi ilmiah |
| `joblib` | $\ge 1.3.0$ | Serialisasi model, kompresi artefak, komputasi paralel |
| `nltk` | $\ge 3.8.0$ | Pra-pemrosesan bahasa alami (tokenisasi, stopwords) |
| `jupyter` / `notebook` | $\ge 1.0.0$ | Lingkungan kerja notebook interaktif |

---

## 📜 Lisensi & Catatan Akademik

Proyek ini disusun dan dipublikasikan untuk keperluan **Tugas 2 Mata Kuliah Machine Learning (Enrichment)**, Program Studi S1 Teknik Komputer, Telkom University.  
Seluruh kode reproduksi mengacu pada materi buku *scikit-learn Cookbook* dengan modifikasi, elaborasi teoretis, dan visualisasi mandiri.
