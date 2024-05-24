# Game Time Diagram

## Context Diagram
![Context Diagram](<DeliverableGameTime/image.png>)
## Container Diagram
![Container Diagram](<DeliverableGameTime/image-1.png>)
## Deployment Diagram
![DeploymentDiagram](<DeliverableGameTime/image-2.png>)
## Risk Storming
![Risk Storming](DeliverableGameTime/image77.png)

Setelah melakukan risk storming, disepakati bahwa arsitektur baru akan menggunakan load balancer untuk mengelola distribusi lalu lintas ke layanan mikro untuk meningkatkan kinerja. Layanan mikro seperti Keranjang Belanja, Gametime App, Penjualan Pembelian, Rating dan Ulasan, serta Sistem Pengelolaan Riwayat, masing-masing akan memiliki fungsionalitas spesifik dan dapat diskalakan secara independen. Setiap layanan mikro akan menggunakan PostgreSQL untuk menjaga konsistensi data dan mendukung skalabilitas. Redis akan digunakan sebagai cache layer untuk meningkatkan kinerja dengan menyimpan data yang sering diakses. Implementasi CI/CD pipelines dan alat pemantauan seperti Prometheus dan Grafana akan digunakan untuk memastikan sistem dapat di-deploy dan dimonitor secara efisien.

## Keranjang

### Keranjang Component Diagram

Berikut adalah diagram untuk komponen pada fitur keranjang
![componentdiagramkeranjang](<DeliverableSurya/image.png>)

### Keranjang Code diagram
Untuk code diagram keranjang adalah sebagai berikut 
![codediagramkeranjang](<DeliverableSurya/codediagramkeranjang.png>)

## Penjualan Pembelian

### Pejualan Pembelian Component Diagram
Berikut adalah diagram untuk komponen pada fitur Penjualan Pembelian
![architecture-PenjualanPembelian Component](https://github.com/B9JagoNgadpro/Modul12Architecture/assets/121223135/af499b37-dee0-4875-a859-a455aae68b8a)

### Penjualan Pembelian Code diagram
![penjualanpembelian3](https://github.com/B9JagoNgadpro/Modul12Architecture/assets/121223135/29ce3b1f-310a-4833-be9a-c4be8ebc65ef)

