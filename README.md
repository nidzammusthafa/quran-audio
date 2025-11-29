# Quran Audio Project

Koleksi audio Al-Quran dari 6 qari yang tersebar di 3 repository GitHub Pages.

## Struktur Repository

Audio dibagi menjadi 3 repository untuk menghindari batas ukuran GitHub:

| Repository | GitHub Pages URL | Qari |
|------------|------------------|------|
| muslimset-murotal-1 | https://nidzammusthafa.github.io/muslimset-murotal-1/ | Ahmed Ajamy, Mishary Alafasy |
| muslimset-murotal-2 | https://nidzammusthafa.github.io/muslimset-murotal-2/ | Muhammad Ayyoub, Muhammad Jibreel |
| muslimset-murotal-3 | https://nidzammusthafa.github.io/muslimset-murotal-3/ | Husary Mujawwad, Minshawi |

## Akses Audio via API

### Format URL
```
https://nidzammusthafa.github.io/{repo}/{qari}/{ayat}.mp3
```

### Parameter
- `{repo}`: Nama repository (`muslimset-murotal-1`, `muslimset-murotal-2`, atau `muslimset-murotal-3`)
- `{qari}`: ID qari (lihat daftar di bawah)
- `{ayat}`: Nomor ayat (1-6236)

### Daftar Qari dan Repository

#### Repository 1 (muslimset-murotal-1)
| ID Qari | Nama Qari | Contoh URL |
|---------|-----------|------------|
| `ahmedajamy` | Ahmed Ajamy | https://nidzammusthafa.github.io/muslimset-murotal-1/ahmedajamy/1.mp3 |
| `alafasy` | Mishary Alafasy | https://nidzammusthafa.github.io/muslimset-murotal-1/alafasy/1.mp3 |

#### Repository 2 (muslimset-murotal-2)
| ID Qari | Nama Qari | Contoh URL |
|---------|-----------|------------|
| `muhammadayyoub` | Muhammad Ayyoub | https://nidzammusthafa.github.io/muslimset-murotal-2/muhammadayyoub/1.mp3 |
| `muhammadjibreel` | Muhammad Jibreel | https://nidzammusthafa.github.io/muslimset-murotal-2/muhammadjibreel/1.mp3 |

#### Repository 3 (muslimset-murotal-3)
| ID Qari | Nama Qari | Contoh URL |
|---------|-----------|------------|
| `husarymujawwad` | Husary Mujawwad | https://nidzammusthafa.github.io/muslimset-murotal-3/husarymujawwad/1.mp3 |
| `minshawi` | Minshawi | https://nidzammusthafa.github.io/muslimset-murotal-3/minshawi/1.mp3 |

## Link Player

Setiap repository memiliki player HTML yang dapat memutar audio dari semua 6 qari:

- [Player Repository 1](https://nidzammusthafa.github.io/muslimset-murotal-1/)
- [Player Repository 2](https://nidzammusthafa.github.io/muslimset-murotal-2/)
- [Player Repository 3](https://nidzammusthafa.github.io/muslimset-murotal-3/)

## Penggunaan

1. Buka salah satu link player di atas
2. Pilih qari dari dropdown
3. Masukkan nomor ayat (1-6236)
4. Tekan play atau Enter

### Keyboard Shortcuts
- `Space`: Play/Pause
- `Arrow Right`: Ayat selanjutnya
- `Arrow Left`: Ayat sebelumnya

## Struktur Folder

```
muslimset-murotal-1/
├── index.html
├── README.md
├── ahmedajamy/
│   ├── 1.mp3
│   ├── 2.mp3
│   └── ... (sampai 6236.mp3)
└── alafasy/
    ├── 1.mp3
    ├── 2.mp3
    └── ... (sampai 6236.mp3)

muslimset-murotal-2/
├── index.html
├── README.md
├── muhammadayyoub/
│   └── ...
└── muhammadjibreel/
    └── ...

muslimset-murotal-3/
├── index.html
├── README.md
├── husarymujawwad/
│   └── ...
└── minshawi/
    └── ...
```

## Credits

Audio oleh [Nidzam Musthafa](https://github.com/Nidzammusthafa)
