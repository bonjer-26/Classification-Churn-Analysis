# Classification-Churn-Analysis
Financial Data Challenge - 2022

LATAR BELAKANG
Challenge ini dibuat atas kerjasama PT.Sharing Vision Indonesia dengan BRI (PT Bank Rakyat Indonesia, Tbk) dengan tujuan:
- Membuka kesempatan untuk peserta dari seluruh indonesia, dari Sabang sampai Marauke untuk merasakan Challenge terhadap real financial use case.

USE CASE
Goal: Membuat model klasifikasi yang dapat menentukan apakah seorang nasabah akan churn atau tidak
Model harus dibuat sekurang-kurangnya meliputi:
1. Exploratory data analysis (EDA)
2. Feature Engineering
3. Modeling
4. Model Evaluation

================

Parameter Tuning

Dalam hal tahap tuning ini, penulis menggunakan metode GeneticSelectionCV dari Library Scikit.learn.
Metode ini digunakan untuk Feature Selection, mengeliminasi sejumlah feature yang digunakan dalam proses pemodelan dengan target: MENINGKATKAN KECEPATAN PEMODELAN.

from genetic_selection import GeneticSelectionCV








