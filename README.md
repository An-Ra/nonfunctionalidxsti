# Performance Test dengan JMeter

Repositori ini berisi pengujian performa API menggunakan Apache JMeter.

## 🛠️ Setup

1. **Download & Install JMeter**
   - Unduh JMeter dari [Apache JMeter](https://jmeter.apache.org/download_jmeter.cgi)
   - Ekstrak dan tambahkan JMeter ke PATH jika perlu

2. **Clone Repository**
   ```bash
   git clone https://github.com/An-Ra/nonfunctionalidxsti.git
   cd nonfunctionalidxsti
   ```

3. **Persiapkan Test Plan**
   - Pastikan file `**.jmx` ada di dalam direktori proyek
   - Buat direktori hasil jika belum ada: `mkdir Results`

## 🚀 Menjalankan Pengujian

Jalankan perintah berikut untuk melakukan pengujian:

```bash
jmeter -n -t **.jmx -l test-dir/report.csv -e -o Results/
