---
title: "WannaCry, Virus Mematikan Pada Masanya  "
date: 2023-09-18T10:22:00+07:00
authors: ['Mazam Ganendra']
tags: ['xx1000']
draft: false
math: true
url: "0041"
---
{{< toc >}}

# Ide Situs Website
Ide untuk membuat situs web ini, saya ingin membuat website bertemakan virus yang sempat menyerang dunia pada tahun 2017 silam yang sangat berbahaya.

## WannaCry
WannaCry adalah jenis ransomware yang terkenal karena serangan massalnya pada sistem komputer pada bulan Mei 2017. Ransomware adalah jenis perangkat lunak berbahaya yang mengenkripsi data pada komputer korban dan kemudian meminta tebusan dalam bentuk uang untuk memberikan kunci dekripsi agar data dapat diakses kembali.

Berikut beberapa poin penting tentang WannaCry:

1. **Tanggal Serangan**: Serangan WannaCry terjadi pada bulan Mei 2017. Serangan ini sangat mengganggu dan menyerang ribuan komputer di seluruh dunia dalam waktu singkat.

2. **Metode Serangan**: WannaCry menyebar melalui eksploitasi kerentanan di sistem operasi Windows. Para penyerang menggunakan kerentanan yang dikenal sebagai "EternalBlue," yang merupakan bagian dari toolkit peretasan yang dikembangkan oleh badan intelijen Amerika Serikat, NSA. Ketika komputer yang menjalankan sistem Windows yang belum diperbarui terinfeksi, WannaCry mengenkripsi data di komputer tersebut dan meminta tebusan dalam bentuk Bitcoin agar korban dapat mendapatkan kunci dekripsi.

3. **Dampak**: Serangan WannaCry memiliki dampak yang signifikan. Banyak institusi dan bisnis di seluruh dunia terkena dampaknya, termasuk rumah sakit, perusahaan, dan lembaga pemerintah. Banyak komputer terinfeksi dan data menjadi tidak dapat diakses.

4. **Reaksi Global**: Serangan WannaCry memicu reaksi global. Beberapa negara dan perusahaan keamanan siber berusaha menghentikan penyebaran ransomware dan memberikan saran tentang cara melindungi komputer dari serangan serupa di masa depan.

Serangan WannaCry menjadi pelajaran penting tentang pentingnya menjaga sistem operasi dan perangkat lunak terbaru dengan pembaruan keamanan, serta mengadopsi praktik keamanan siber yang baik untuk melindungi diri dari ancaman ransomware dan serangan siber lainnya.


## Metode Penyerangan WannaCry
{{<mermaid align="left">}}
graph LR;
    A[WannaCry] -->|Target| B(Sistem Windows yang belum diperbarui)
    B --> C{Permintaan Tebusan}
    C --> D[300 Dolar]
    C --> E[600 Dolar]
{{< /mermaid >}}


## Beberapa Negara yang Terkena Dampak Virus WannaCry
{{< chart 90 200 >}}
{
    type: 'bar',
    data: {
        labels: ['Indonesia', 'Rusia', 'Iran', 'Vietnam', 'Spanyol', 'Turki'],
        datasets: [{
            label: 'Bar Chart',
            data: [4150, 2150, 2250, 3500, 2800, 4900],
            backgroundColor: [
                'rgba(255, 99, 132, 0.2)',
                'rgba(54, 162, 235, 0.2)',
                'rgba(255, 206, 86, 0.2)',
                'rgba(75, 192, 192, 0.2)',
                'rgba(153, 102, 255, 0.2)',
                'rgba(255, 159, 64, 0.2)'
            ],
            borderColor: [
                'rgba(255, 99, 132, 1)',
                'rgba(54, 162, 235, 1)',
                'rgba(255, 206, 86, 1)',
                'rgba(75, 192, 192, 1)',
                'rgba(153, 102, 255, 1)',
                'rgba(255, 159, 64, 1)'
            ],
            borderWidth: 1
        }]
    },
    options: {
        maintainAspectRatio: false,
        scales: {
            yAxes: [{
                ticks: {
                    beginAtZero: true
                }
            }]
        }
    }
}
{{< /chart >}}


## Gambar Virus WannaCry
![](https://farmalkes.kemkes.go.id/wp-content/uploads/2021/02/wannacry-ransomware.jpg)
![](https://www.healthcareitnews.com/sites/hitn/files/WannaCry-lockscreen712_0.png)

## Pengenalan Virus WannaCry
{{< youtube I5Wxh-rCzrY >}}

## Informasi Singkat WannaCry
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
| No. | Tipe Serangan     | Tanggal Serangan | Dampak        | Target                                       | Metode Serangan                          | Permintaan Tebusan |
|-----|-------------------|-------------------|---------------|----------------------------------------------|-------------------------------------------|--------------------|
| 1   | Ransomware        | Mei 2017          | Besar         | Sistem Windows yang belum diperbarui       | Memanfaatkan kerentanannya yang belum diperbarui | Bitcoin (sekitar $300 - $600) |
| 2   | Penyebaran        | Melalui SMB (Server Message Block) | Menyebar secara cepat melalui jaringan komputer | Mencari sistem yang rentan, termasuk yang belum diperbarui atau tidak memiliki patch keamanan |
| 3   | Pencipta           | Kelompok peretas anonim (identitas tidak diketahui) |                                                  |                                            |
| 4   | Daftar Kerentanan | MS17-010 (EternalBlue) | Kerentanan terkait dengan protokol SMB di Windows |                                                   |                                            |
| 5   | Dampak Terkenal   | Serangan WannaCry menginfeksi lebih dari 200.000 komputer di 150 negara dalam beberapa hari setelah serangan. |                                            |                                            |
| 6   | Keamanan          | Microsoft segera merilis pembaruan (patch) untuk mengatasi kerentanan yang dieksploitasi oleh WannaCry. |                                            |                                            |
| 7   | Tindakan Pencegahan | - Pastikan sistem Windows Anda selalu diperbarui dengan pembaruan keamanan terbaru. | - Lakukan backup data secara teratur. - Waspadai email dan lampiran yang mencurigakan. - Gunakan perangkat lunak keamanan yang kuat. |
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------



.virus-wannacry {
  animation: moveRight 4s linear infinite;
}

@keyframes moveRight {
  0% {
    transform: translateX(0);
  }
  100% {
    transform: translateX(100%);
  }
}
<svg class="virus-wannacry" xmlns="http://www.w3.org/2000/svg" width="100" height="100" viewBox="0 0 100 100">
  <!-- Isi elemen SVG Anda di sini -->
</svg>


## animation
{{< html >}}
<svg style="background: #eee;">
  <rect x="0" y="50" width="50" height="50">
    <animate
      attributeName="x"
      from="0" to="300"
      begin="0s" dur="2s"
      repeatCount="indefinite" />
  </rect>
</svg>
{{< /html >}}

## SVG
{{< html >}}
<svg style="background: #ccc;" width="200" height="200">
  <rect x="40" y="25" width="100" height="60"
  style="
    fill: lightblue;">
  </rect>
  <rect x="70" y="45" width="100" height="60"
  style="
    fill: blue;
    fill-opacity: 0.2;">
  </rect>
  <rect x="120" y="65" width="100" height="60"
  style="
    fill: blue;
    fill-opacity: 0.5;">
  </rect>
</svg>
{{< /html >}}


{{< html >}}
<svg style="background: magenta;" width="200" height="200">
  <rect width="50" height="50"></rect>
  <rect x="100" y="20" width="50" height="50" fill="blue"></rect>
</svg>
{{< /html >}}

## Link
+ [Google](https://www.google.com/)
+ [GitHub](https://github.com)

## 1st section
..

## 2nd section
..

## 3rd section
Content of first section.