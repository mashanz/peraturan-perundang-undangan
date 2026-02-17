# Hierarki Peraturan Perundang-undangan Indonesia

🇮🇩 **Indonesian Legal Regulations Hierarchy** - AI-Agent Friendly Structure

## 📋 Overview

Repository ini berisi struktur hierarki peraturan perundang-undangan Indonesia yang terorganisir dalam format yang ramah untuk analisis AI-agent. Tujuannya adalah memudahkan analisis kepatuhan dan aturan hukum Indonesia saat ini.

*This repository contains the Indonesian legal regulations hierarchy organized in an AI-agent friendly structure. The goal is to facilitate analysis of Indonesia's current compliance and legal rules.*

## 🏛️ Legal Hierarchy (Hierarki Hukum)

Berdasarkan UU No. 12 Tahun 2011 tentang Pembentukan Peraturan Perundang-undangan, berikut urutan hierarki dari yang tertinggi:

1. **UUD 1945** - Undang-Undang Dasar Negara Republik Indonesia Tahun 1945
2. **TAP MPR** - Ketetapan Majelis Permusyawaratan Rakyat  
3. **UU/Perppu** - Undang-Undang atau Peraturan Pemerintah Pengganti Undang-Undang
4. **PP** - Peraturan Pemerintah
5. **Perpres** - Peraturan Presiden
6. **Perda Provinsi** - Peraturan Daerah Provinsi
7. **Perda Kabupaten/Kota** - Peraturan Daerah Kabupaten/Kota

### 📍 Posisi Peraturan Menteri (Permen)

Permen tidak termasuk dalam 7 hierarki utama di atas, namun tetap diakui keberadaannya dan mempunyai kekuatan hukum mengikat sepanjang:
- Diperintahkan oleh Peraturan Perundang-undangan yang lebih tinggi, atau
- Dibentuk berdasarkan kewenangan (sesuai Pasal 8 UU No. 12 Tahun 2011)

## 📁 Repository Structure

```
📂 peraturan-perundang-undangan/
├── 📄 README.md                 # Overview dan panduan
├── 📂 hierarchy/                # Detail setiap tingkat hierarki
│   ├── 01-uud-1945.md          # Undang-Undang Dasar 1945
│   ├── 02-tap-mpr.md           # Ketetapan MPR  
│   ├── 03-uu-perppu.md         # UU dan Perppu
│   ├── 04-pp.md                # Peraturan Pemerintah
│   ├── 05-perpres.md           # Peraturan Presiden
│   ├── 06-perda-provinsi.md    # Perda Provinsi
│   ├── 07-perda-kabupaten.md   # Perda Kabupaten/Kota
│   └── 08-permen.md            # Peraturan Menteri
├── 📂 permen/                  # **Peraturan Menteri Detail**
│   └── 📂 kominfo/             # Kementerian Komunikasi dan Digital
│       ├── README.md           # Overview & struktur
│       ├── active-regulations.md # Daftar lengkap peraturan aktif
│       ├── change-history.md   # Riwayat perubahan (Git-tracked)
│       └── critical-regulations.md # Peraturan kritis prioritas tinggi
├── 📂 analysis/                # Framework analisis
│   ├── compliance-framework.md  # Framework kepatuhan
│   └── ai-analysis-guide.md    # Panduan analisis AI
├── 📂 compliance/              # Tracking kepatuhan
│   └── current-status.md       # Status terkini
└── 📂 data/                    # Data terstruktur
    └── hierarchy.json          # Data JSON untuk AI
```

## 🚀 **NEW: Detailed Permen Tracking**

### Kementerian Komunikasi dan Digital
📂 **[Peraturan Menteri Kominfo/Komdigi](permen/kominfo/)** - Complete tracking system with:

- **[📋 Active Regulations](permen/kominfo/active-regulations.md)** - 152+ active regulations across 8 categories
- **[🔄 Change History](permen/kominfo/change-history.md)** - Git-tracked changes with cross-references  
- **[🚨 Critical Regulations](permen/kominfo/critical-regulations.md)** - High-impact regulations requiring close monitoring
- **[📊 Real-time Compliance](permen/kominfo/README.md#statistics)** - Status tracking and analytics

**Key Features:**
✅ **Hyperlinked cross-references** between related regulations  
✅ **Git history tracking** for all changes with reasoning  
✅ **Impact analysis** for business and compliance implications  
✅ **AI-ready metadata** for automated monitoring  
✅ **Critical alert system** for high-priority regulatory changes  

**Coverage includes:** PSE Platform regulation, PDP implementation, Digital transformation, Cybersecurity, Broadcasting, Telecommunications, and more.

## 🤖 AI-Agent Friendly Features

- **Structured Markdown**: Setiap dokumen dalam format markdown dengan metadata
- **Hierarchical Organization**: Folder structure mengikuti hierarki hukum  
- **Machine Readable**: JSON data untuk pemrosesan otomatis
- **Compliance Tracking**: Framework untuk tracking kepatuhan
- **Analysis Framework**: Panduan untuk analisis sistematis
- **Detailed Permen Tracking**: Real-time ministerial regulation monitoring

## 🎯 Use Cases

1. **Legal Compliance Analysis** - Analisis kepatuhan terhadap hierarki hukum
2. **Regulatory Impact Assessment** - Penilaian dampak regulasi
3. **Legal Research** - Penelitian hukum terstruktur
4. **AI-Powered Legal Analysis** - Analisis hukum berbasis AI
5. **Government Transparency** - Transparansi regulasi pemerintah

## 📚 References

- UU No. 12 Tahun 2011 tentang Pembentukan Peraturan Perundang-undangan
- UU No. 15 Tahun 2019 tentang Perubahan atas UU No. 12 Tahun 2011
- Hierarki Peraturan Perundang-undangan Indonesia

## 🤝 Contributing

Contributions welcome! Please:
1. Fork repository ini
2. Buat branch untuk perubahan Anda
3. Submit pull request dengan deskripsi yang jelas
4. Pastikan mengikuti struktur yang ada

## 📄 License

MIT License - Feel free to use for legal research and analysis

---

**Disclaimer**: Repository ini dibuat untuk tujuan edukasi dan penelitian. Selalu rujuk ke sumber hukum resmi untuk keperluan legal formal.

*This repository is created for educational and research purposes. Always refer to official legal sources for formal legal matters.*