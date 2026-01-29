# Natural Language Processing Projects

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

A collection of NLP and text mining projects. These projects span text classification with transfer learning and graph-based recommendation systems, demonstrating practical applications of modern NLP techniques.

---

## Project Index

| Project | Description | Technique | Dataset |
|---------|-------------|-----------|---------|
| [Quora Smart Compose](projects/quora-smart-compose/) | Classify sincere vs. insincere questions on Quora | fast.ai / Transfer Learning | Kaggle Quora Insincere Questions |
| [Medium Article Recommender](projects/medium-article-recommender/) | Graph-based article recommendation system | Graph Theory / NetworkX | Medium Articles |

---

## Getting Started

Each project is self-contained under `projects/<project-name>/`. To get up and running:

```bash
# 1. Clone the repository
git clone https://github.com/shivamakhauri04/nlp.git

# 2. Navigate to the project of interest
cd nlp/projects/<project-name>

# 3. Install dependencies
pip install -r requirements.txt
```

> **Tip:** It is recommended to create a virtual environment (`venv` or `conda`) before installing dependencies to avoid conflicts between projects.

Refer to each project's own README for detailed usage instructions, data download steps, and training commands.

---

## Repository Structure

```
nlp/
├── README.md
├── LICENSE
├── .gitignore
├── .gitattributes
└── projects/
    ├── quora-smart-compose/
    └── medium-article-recommender/
```

Each project follows a standard layout with its own `README.md`, `requirements.txt`, source code, and data directories.

---

## License

This project is licensed under the **MIT License** -- see the [LICENSE](LICENSE) file for details.

---

Copyright (c) 2019 Shivam Akhauri
