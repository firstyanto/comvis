# Perbandingan NN vs CNN vc ViT pada Computer Vision

Penggunaan Deep Learning dimulai pada tahun 1989 dimana jaringan saraf konvolusional (CNN) pertama, LeNet, dikembangkan oleh Yann LeCun dan timnya untuk pengenalan karakter tulisan tangan.
Pada tulisan kali ini, kita akan mencoba membandingkan 3 (tiga) model deep learning untuk computer vision dengan menggunakan Pytorch, yaitu :
1. Convolution Neurat Network (CNN) dengan menggunakan arsitektur LeNet
2. Neural Network (NN) saja
3. Vision Transformer (Vit)

Seluruh Model dibuat dari scracth, yang bertujuan untuk eksperimen lainnya di kemudia hari. Ketiga model tersebut juga tidak mengharus resize gamabar ke dimensi tertentu sehingga komputasi untuk training ketiga model tersebut masih nyaman dilakukan dengan CPU. Dataset yang digunakan adalah dataset MNIST yaitu dataset yang sama digunakan oleh Yann LeCun dalam melatih dan menguji LeNet. Di dalam dataset MNIST terdapat 6000 gambar angka yang berupa tulisan tangan mulai dari angka 0 (nol) sampai dengan 9 (sembilan).

Hasil pengujian dari ketiga model tersebut ditampilkan dalam tabel berikut :

| Rank | Model     |  Test Accuracy |  Test Loss  | Validation Accuracy | Validation Loss |
|-----:|-----------|----------------|-------------|---------------------|-----------------|
|     1| CNN-LeNet | 0.99548        | 0.01385     | 0.99019             | 0.04113         |
|     2| NN        |                |             |                     |                 |
|     3| Vit       |                |             |                     |                 |

<piture>
<p align="center">
<img src="https://github.com/firstyanto/comvis/blob/main/assets/lenet_acc_loss.png" width="480" height="480"/>
</p>
</piture>
