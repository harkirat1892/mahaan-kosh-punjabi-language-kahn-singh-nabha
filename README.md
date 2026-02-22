# Mahan Kosh JSON Dataset

A complete, machine-readable JSON dataset of the **Gur Shabad Ratanakar Mahan Kosh**, the foundational encyclopedia of Sikh literature, compiled by **Bhai Kahn Singh Nabha**.

## 📖 About the Mahan Kosh
The *Mahan Kosh* is an unparalleled reference work for the Punjabi language and Sikh theology. It was completed in 1926 and first published in 1930. Covering over 60,000 entries, it provides etymologies, historical contexts, and definitions for terms found in the Guru Granth Sahib and related literature.

## 🚀 Dataset Overview
This repository provides the full Mahan Kosh as a single audited JSON file and sharded alphabet-based files for high-performance developer integration.

- **Total Entries**: 63,622
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
