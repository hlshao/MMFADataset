# MMFADataset
Dataset of Misleading Medical and Food Advertisements (MMFA-2025), compiled for research and teaching purposes.
📊 Misleading Medical and Food Advertisements Dataset (MMFA-2025)

This repository hosts the Misleading Medical and Food Advertisements Dataset (MMFA-2025), compiled for research and teaching purposes at Taipei Medical University.

📖 About

The dataset was created to support research on text classification, natural language processing (NLP), health law, and regulation studies.

It consists of:

Positive Samples (Label = 1): Misleading medical or food advertisements collected from county and city government violation reports.

Negative Samples (Label = 0): Normal advertisements collected from public online platforms (e.g., Facebook, Yahoo).

This dataset was originally prepared for the 2025 course “Smart Biomedical Project Practicum (智慧生醫專題實作)” at Taipei Medical University.

🗂️ Data Preparation

Collection:

Positive samples: government-published violation cases.

Negative samples: publicly available advertisements.

Preprocessing:

Removal of overly short sentences.

Normalization by deleting redundant punctuation.

Manual inspection to exclude unreasonable outliers.

📦 Dataset Format

Each entry is represented as a row in CSV/JSON:

Field	Description
id	Unique identifier
text	Advertisement content
label	1 = Misleading / 0 = Normal
📚 Usage Policy

The dataset is provided for academic research and educational purposes.

For additional details or commercial usage, please contact the maintainer.

📈 Potential Applications

Misleading advertisement detection (binary classification).

Health law and policy analysis.

NLP benchmark tasks for Chinese-language text.

Comparative studies of public communication in health domains.

📌 Citation

If you use this dataset, please cite it as:

APA Style
Shao, H.-L. (2025). Misleading Medical and Food Advertisements Dataset (MMFA-2025). Taipei Medical University.

BibTeX

@misc{Shao2025MMFA,
  author       = {Hsuan-Lei Shao},
  title        = {Misleading Medical and Food Advertisements Dataset (MMFA-2025)},
  year         = {2025},
  institution  = {Taipei Medical University},
  note         = {Dataset available for academic use. Contact for commercial usage.}
}

📜 License

This dataset is distributed under the Apache License 2.0.

You may use, modify, and distribute this dataset, provided that you:

Give proper attribution to the dataset author.

Include a copy of the license in any redistribution.

Indicate any modifications made to the dataset.

👉 Full License Text

For commercial use or redistribution, please contact the maintainer: hlshao@tmu.edu.tw
.

📬 Contact

Maintainer: Hsuan-Lei Shao (邵軒磊)

Affiliation: Graduate Institute of Health and Biotechnology Law, Taipei Medical University

Email: hlshao@tmu.edu.tw

ORCID: 0000-0002-7101-5272
