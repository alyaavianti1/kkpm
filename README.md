## Deskripsi

Proyek ini merupakan implementasi algoritma Multilayer Perceptron (MLP) menggunakan library scikit-learn untuk mengklasifikasikan tingkat obesitas seseorang berdasarkan kebiasaan makan, gaya hidup, dan data fisik. Proyek ini merupakan bagian dari tugas mata kuliah Komputasi dan Kecerdasan Pembelajaran Mesin (KKPM).

## Dataset
- **Nama:** Estimation of Obesity Levels Based on Eating Habits and Physical Condition
- **Sumber:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/datasets)
- **Jumlah data:** 2.111 sampel
- **Jumlah fitur:** 16 fitur
- **Target:** 7 kelas tingkat obesitas
  - Insufficient Weight
  - Normal Weight
  - Overweight Level I
  - Overweight Level II
  - Obesity Type I
  - Obesity Type II
  - Obesity Type III


## Arsitektur MLP
| Parameter | Nilai |
|---|---|
| Hidden Layers | 3 layer (128, 64, 32 neuron) |
| Activation Function | ReLU |
| Max Iterasi | 500 |
| Data Training | 80% (1.688 data) |
| Data Testing | 20% (423 data) |

## Hasil
| Metrik | Nilai |
|---|---|
| Accuracy | 92.91% |
| Macro F1-Score | 0.93 |
| Weighted F1-Score | 0.93 |

## Tools & Library
- Python 3
- Google Colab
- scikit-learn
- pandas
- numpy
- matplotlib
- seaborn
