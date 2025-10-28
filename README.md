# Perbandingan NN vs CNN vc ViT pada Computer Vision

Penggunaan Deep Learning dimulai pada tahun 1989 dimana jaringan saraf konvolusional (CNN) pertama, LeNet, dikembangkan oleh Yann LeCun dan timnya untuk pengenalan karakter tulisan tangan.

Pada tulisan kali ini, kami akan mencoba membandingkan 3 (tiga) model deep learning untuk computer vision dengan menggunakan Pytorch, yaitu :
1. Convolution Neurat Network (CNN) dengan menggunakan arsitektur LeNet
2. Neural Network (NN) saja
3. Vision Transformer (Vit)

Seluruh Model dibuat dari scracth, yang bertujuan untuk eksperimen lainnya di kemudian hari. Ketiga model tersebut juga tidak mengharuskan resize gambar ke dimensi tertentu, sehingga komputasi untuk training ketiga model tersebut masih nyaman dilakukan dengan CPU. Dataset yang digunakan adalah dataset MNIST yaitu dataset yang sama digunakan oleh Yann LeCun dalam melatih dan menguji LeNet. Di dalam dataset MNIST terdapat 6000 gambar angka yang berupa tulisan tangan mulai dari angka 0 (nol) sampai dengan 9 (sembilan).

Hasil pengujian dari ketiga model tersebut ditampilkan dalam tabel berikut :

| Rank | Model     |  Test Accuracy |  Test Loss  | Validation Accuracy | Validation Loss |
|-----:|-----------|----------------|-------------|---------------------|-----------------|
|     1| CNN-LeNet | 0.99548        | 0.01385     | 0.99019             | 0.04113         |
|     2| NN        | 0.99198        | 0.02333     | 0.97856             | 0.08939         |
|     3| ViT       | 0.90568        | 0.29639     | 0.90575             | 0.28151         |
###### *Ket : Nilai Accuracy dan Loss yang ditampilkan adalah nilai terbaik dari pengujian

Berikut adalah Grafik Hasil uji Accuracy dan Loss untuk Test dan Validasi dari masing-masing model :

---
### LeNet
![Hasi uji Accuracy dan Loss mode LeNet](https://github.com/firstyanto/comvis/blob/main/assets/lenet_acc_loss.png)(https://github.com/firstyanto/comvis/blob/main/CNN_Lenet_MNIST.ipynb)

----
### NN
![Hasi uji Accuracy dan Loss mode LeNet](https://github.com/firstyanto/comvis/blob/main/assets/nn_acc_loss.png)(https://github.com/firstyanto/comvis/blob/main/CNN_MNIST.ipynb)

---
### Vit
![Hasi uji Accuracy dan Loss mode LeNet](https://github.com/firstyanto/comvis/blob/main/assets/vit_acc_loss.png)(https://github.com/firstyanto/comvis/blob/main/ViT_MNIST.ipynb)

----


> [!NOTE]
> Tulisan ini dibuat untuk pemenuhan tugas Mata Kuliah Computer Vision
> 
> Universita Pamulang (Unpam), Tahun 2025
> 
> Nama : Doni Fristiyanto
> 
> Nim  : 241012000122 
