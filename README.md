
# SKYRAG: Separated Keyword Retrieval Augmentation Generation System

![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)
![Jupyter Notebooks](https://img.shields.io/badge/notebooks-Jupyter-orange)
![License](https://img.shields.io/badge/license-MIT-green)
![Issues](https://img.shields.io/github/issues/leonardcl/skyrag)
![Stars](https://img.shields.io/github/stars/leonardcl/skyrag)


**SKYRAG** is an advanced system for generating personalized learning paths by leveraging Large Language Models (LLMs) integrated with retrieval mechanisms. SKYRAG retrieves relevant course materials from Massive Open Online Course (MOOC) platforms and tailors them to individual learner profiles, addressing common issues like hallucinations and content irrelevance in LLMs.

Compared to Naïve RAG, SKYRAG achieves superior performance in terms of accuracy, relevance, and user satisfaction, as demonstrated in human evaluations across multiple educational domains.

## Key Features
- **Advanced Retrieval**: SKYRAG enhances the retrieval process using Separated Keyword Retrieval techniques.
- **Personalized Learning**: Tailored learning paths based on individual learner profiles and preferences.
- **LLM Integration**: Utilizes powerful language models to ensure coherent and relevant content generation.
- **Performance Gains**: Outperforms Naïve RAG in accuracy, relevance, and user satisfaction.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Notebook Overview](#notebook-overview)
- [Contributing](#contributing)
- [License](#license)

## Installation

To install and run SKYRAG locally, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/leonardcl/skyrag.git
   ```
2. Navigate into the project directory:
   ```bash
   cd skyrag
   ```
3. (Optional) Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
4. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

You can explore and run SKYRAG using the provided Jupyter notebooks. Here's how to start Jupyter and run the notebooks:

1. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Open the notebook `skyrag_demo.ipynb` to see a demonstration of SKYRAG in action.

   - The notebook will walk you through the retrieval and learning path generation process.
   - Ensure you have internet access to retrieve data from MOOC platforms.

## Notebook Overview

- **`skyrag_demo.ipynb`**: Demonstration of SKYRAG's main functionalities.
- **`skyrag_analysis.ipynb`**: Detailed performance analysis and comparison with Naïve RAG.
- **`skyrag_utils.py`**: Utility functions for keyword retrieval, LLM integration, and MOOC alignment.

## Contributing

We welcome contributions to SKYRAG! Please follow these steps if you'd like to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add a new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

Please make sure to update tests as appropriate and follow the [Contributor Code of Conduct](CODE_OF_CONDUCT.md).

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

**SKYRAG** is a significant advancement in educational technology, designed to improve the quality of personalized learning paths. We hope this project will contribute to the growing field of AI-driven learning systems.
