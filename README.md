# Grammar Checker Engine

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![NLP](https://img.shields.io/badge/NLP-Powered-purple)
![License](https://img.shields.io/badge/License-MIT-green)

A grammar checking engine that analyzes text for grammatical errors, spelling mistakes, and style issues. Combines rule-based parsing with NLP techniques to provide accurate corrections and writing improvement suggestions.

---

## Features

- **Grammar Detection** -- Identifies subject-verb agreement, tense, and syntax errors
- **Spelling Correction** -- Context-aware spell checking with dictionary support
- **Style Suggestions** -- Flags passive voice, wordiness, and readability issues
- **Punctuation Checks** -- Detects missing or misplaced commas, periods, and quotes
- **Multi-Language** -- Supports English with extensible language modules
- **API Interface** -- Expose grammar checking as a REST API endpoint

---

## Tech Stack

| Technology | Purpose |
|---|---|
| Python 3.9+ | Core runtime |
| NLP Libraries | Text analysis and parsing |
| Rule Engine | Grammar rule matching |
| CSS3 | UI theming |
| Makefile | Build and test automation |

---

## Quick Start

```bash
# Clone the repository
git clone https://github.com/razinahmed/grammar-checker-engine.git
cd grammar-checker-engine

# Install dependencies
pip install -r requirements.txt

# Check grammar in a file
python main.py --input document.txt
```

---

## Project Structure

```
grammar-checker-engine/
├── styles/
│   └── theme.css           # UI theme configuration
├── Makefile                # Build and test commands
├── LICENSE                 # MIT License
├── SECURITY.md             # Security policy
└── README.md
```

---

## Usage

```bash
# Build the project
make build

# Run tests
make test
```

---

## Contributing

1. Fork the repository
2. Create a feature branch -- `git checkout -b feature/your-feature`
3. Commit your changes -- `git commit -m "feat: add new feature"`
4. Push and open a Pull Request

---

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

**Built by [Razin Ahmed](https://github.com/razinahmed)**
