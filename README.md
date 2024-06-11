# Route Optimization Engine

Repositori ini menyelesaikan route optimization engine menggunakan Openstreetmap dan library OR-Tools. Data asli adalah data sales field 317 rows x 8 columns. Silakan jalankan saja notebook main.ipynb, week 2, week 3, dan week 4 karena saya membaginya agar cepat running.


VRP adalah masalah optimasi klasik di mana sejumlah kendaraan bertugas untuk mengunjungi beberapa lokasi untuk meminimalkan total jarak yang dilalui.

## Requirements
* Python Notebook
* Conda
* Git (optional)

## Installation
Clone repository:
```bash
git clone <repository_url>
cd <repository_directory>
```
Membuat dan aktivasi Conda environment menggunakan file env.yaml:
```bash
conda env create -f env.yaml
conda activate demo-sales-field
```

### Example Data
Sampel input data (```data\input\Field Sales_template (3) BWI001.xlsx```) terdapat latitude dan longitude dari koordinat sales, ID, dan lain-lain. Data tersebut dibaca dari file xlsx dan digunakan untuk menghitung rute optimal. Namun, perlu dianalisis dahulu.