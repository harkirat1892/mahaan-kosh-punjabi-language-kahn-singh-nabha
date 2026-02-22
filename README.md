# Mahan Kosh JSON Dataset

A complete, machine-readable JSON dataset of the **Gur Shabad Ratanakar Mahan Kosh**, the foundational encyclopedia of Sikh literature, compiled by **Bhai Kahn Singh Nabha**.

## 🖋️ Behind the Masterpiece: Bhai Kahn Singh Nabha (1861–1938)
The *Mahan Kosh* is not just a dictionary; it is a monumental feat of individual scholarship. **Bhai Kahn Singh Nabha**, a towering figure in Sikh intellectual history, dedicated **14 years** (1912–1926) to its compilation. 

To ensure the work's completion, he resigned from his high-ranking state services (including roles as a foreign minister and judge) to work full-time on this "encyclopedia of Sikh literature." 

- **Monumental Effort**: The research spanned 14 years, culminating in a manuscript completed in February 1926.
- **Historic Publication**: First printed in 1927 and released in four magnificent volumes in 1930.
- **Academic Rigor**: It contains over 64,000 entries, providing etymologies derived from Sanskrit, Arabic, Persian, and various Indian vernaculars.
- **Legacy**: It remains the ultimate authority for scholars, researchers, and seekers of the Guru Granth Sahib's wisdom.

## 🚀 Dataset Overview
This repository provides the full Mahan Kosh as a single audited JSON file and sharded alphabet-based files for high-performance developer integration.

- **Total Entries**: 63,622 (Audited & Verified)
- **Formats**: Single JSON and Sharded (A-Z) JSON
- **Fields**: 
  - `id`: Unique identifier
  - `word`: Gurmukhi term
  - `roman`: Romanized transliteration
  - `hindi`: Devanagari transliteration
  - `description`: The full definition in Gurmukhi
  - `description_hindi`: Romanized/Hindi representation of the description

## 📂 Structure
```text
mahan-kosh-json/
├── mahan_kosh_complete.json    # The full master dataset
├── data/                       # Sharded JSON files for each letter
│   ├── ਮ.json
│   ├── ਸ.json
│   └── ...
└── LICENSE                     # MIT License
```

## ⚖️ Legal & Attribution
The original text of the *Mahan Kosh* (1930) is in the **Public Domain**. 

### Special Thanks
The initial digitization of this dataset was made possible by the pioneering efforts of **SearchGurbani.com**. This repository serves as an independent, audited extraction of that digital effort, intended for offline preservation and mobile application development within the Sikh tech community.

## 🛠 Usage
This dataset is designed for zero-dependency integration. You can directly fetch the letter-specific shards in your Flutter, React, or Mobile apps to avoid loading the full master file into memory.

---
*Maintained with ❤️ for the Gurbani tech community.*
