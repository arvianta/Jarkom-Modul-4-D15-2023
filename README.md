# **Lapres Praktikum Jarkom Modul 4 Kelompok D15**

### **Anggota Kelompok**

| **Nama**                  | **NRP**    |
| ------------------------- | ---------- |
| Rayhan Arvianta Bayuputra | 5025211217 |
| Yehezkiel Wiradhika       | 5025201086 |

## Daftar Isi

- [CIDR](#Konfigurasi-CIDR-pada-GNS3)
- [VLSM](#Konfigurasi-VLSM-pada-CPT)


## Konfigurasi CIDR pada GNS3

### 1. Tentukan subnet yang ada dalam topologi dan lakukan labelling netmask terhadap masing-masing subnet

<img src="./assets/gns3.png" />

### 2. Hitung pembagian IP dengan pohon berdasarkan penggabungan subnet yang telah dilakukan

<img src="./assets/cidr_tree.png" />

Berdasarkan penghitungan, maka didapatkan pembagian IP sebagai berikut.

<img src="./assets/cidr_ip.png" />


## Konfigurasi VLSM pada CPT

### 1. Tentukan subnet yang ada dalam topologi dan lakukan labelling netmask terhadap masing-masing subnet

![cpt](./assets/cpt.png)

### 2. Hitung jumlah client per subnet

![jumlah_ip_subnet](./assets/jumlah_ip_subnet.png)

### 3. Buat VLSM Tree

![vlsm_tree](./assets/vlsm_tree.png)

### 4. Pembagian NID, Netmask, dan BID dari setiap subnet

![vlsm_ip_subnet](./assets/vlsm_ip_subnet.png)

### 5. Pembagian IP Client per subnet

![vlsm_ip_client](./assets/vlsm_ip_client.png)

### 6. Routing via routers untuk connecting semua subnet

![vlsm_routing_cpt](./assets/vlsm_routing_cpt.png)

> Cuplikan routing diatas hanya cuplikan kecil dari routing pada setiap router. Untuk lebih lengkapnya dapat diakses dari file .pkt yang tersedia.