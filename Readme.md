# Pengenalan Ras Kucing Scottish Fold Menggunakan Metode Histogram of Oriented Gradients dan Jaringan Saraf Tiruan

Terdiri dari 2 file program dalam bentuk Jupyter Notebook.
File pertama digunakan untuk training serta testing keseluruhan data.
File kedua digunakan untuk testing spesifik data dengan model hasil training.

## Installation

Install python 3.6

Install Jupyter Notebook

Install opencv

Dengan menggunakan package manager [pip](https://pip.pypa.io/en/stable/) install library berikut.
```bash
pip install scikit-learn
pip install matplotlib
pip install scikit-image
pip install numpy
```

## Usage

### Parameter
#### File Pertama [ HOG - ANN (train-test).ipynb ]
Ubah ``path_data_train`` dan ``path_data_test`` berdasarkan folder yang digunakan untuk training dan testing.

Ubah parameter HOG ``image_size`` untuk resize gambar, ``orientations`` untuk nilai bins, ``pixels_per_cell`` dan ``cells_per_block`` sebagai parameter HOG.

Ubah parameter JST dengan penyesuaian variabel ``max_epoch``, ``hidden_layer_sizes``, ``activation``, ``solver``, ``alpha``, ``learning_rate``, dan ``random_state``.

Untuk menggunakan k-cross validation dapat mengubah parameter ``k-fold_cross-validation``.

Setelah semua parameter disesuaikan, Run All program Jupyter Notebook.

#### File Kedua [ HOG - ANN (Pengujian 1 Citra).ipynb ]
Ubah parameter HOG  ``orientations``, ``pixels_per_cell`` dan ``cells_per_block`` berdasarkan saat training.

Ubah parameter ``path_model`` berdasarkan path model yang akan digunakan.

Ubah parameter ``path_image`` berdasarkan path gambar yang akan digunakan untuk test.

Setelah semua parameter disesuaikan, Run All program Jupyter Notebook.

## License
- [Creative Commons Attribution 3.0 Unported license](https://creativecommons.org/licenses/by/3.0/)

- [MIT](https://choosealicense.com/licenses/mit/)
