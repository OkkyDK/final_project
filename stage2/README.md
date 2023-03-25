# Stage 2 - Online Shoppers Purchasing Intention 

Selain melakukan pemisahan antara kolom feature dan target dalam stage ini dilakukan pula 

## Data Preprocessing

### A. Handle missing values
Menangani missing value sudah tepat dimana semua kolom tidak mempunyai missing value sehingga tidak perlu dilakukan penanganan

### B. Handle duplicated data
Penanganan outlier sesuai dengan kebutuhan namun secara umum data outlier dapat membuat machine focus pada outlier sehingga mengakibatkan output menjadi tidak baik. Oleh karena itu outlier sebaiknya didrop.

### C. Handle outliers
Penanganan outlier sesuai dengan kebutuhan namun secara umum data outlier dapat membuat machine focus pada outlier sehingga mengakibatkan output menjadi tidak baik. Oleh karena itu outlier sebaiknya didrop.

### D. Feature transformation
Proses feature transformasi dilakukan untuk data Xtrain (data feature untuk train) begitu juga encoding

### E. Feature encoding
Tipe kolom weekend di rubah dari float menjadi integer

## F. Handle class imbalance
Melakukan handling class imbalance menggunakan over sampling karena nilai True pada kolom target sangat kecil sekitar 15%.

# Feature Enginering

### A. Feature selection (membuang feature yang kurang relevan atau redundan)
Terdapat 6 kolom feature yang di drop karena redundant dan korelasi dengan target mendekati 0 sehingga feature tersebut tidak berpengaruh
Menghapus baris yang mempunyai nilai Other pada kolom VisitorType