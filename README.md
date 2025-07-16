# LLM R Notebook

[![GitHub stars](https://img.shields.io/github/stars/simonpierreboucher02/llm_R_notebook-main?style=social)](https://github.com/simonpierreboucher02/llm_R_notebook-main/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/simonpierreboucher02/llm_R_notebook-main?style=social)](https://github.com/simonpierreboucher02/llm_R_notebook-main/network/members)
[![GitHub issues](https://img.shields.io/github/issues/simonpierreboucher02/llm_R_notebook-main)](https://github.com/simonpierreboucher02/llm_R_notebook-main/issues)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/simonpierreboucher02/llm_R_notebook-main)](https://github.com/simonpierreboucher02/llm_R_notebook-main/pulls)
[![GitHub license](https://img.shields.io/github/license/simonpierreboucher02/llm_R_notebook-main)](https://github.com/simonpierreboucher02/llm_R_notebook-main/blob/main/LICENSE)
[![GitHub last commit](https://img.shields.io/github/last-commit/simonpierreboucher02/llm_R_notebook-main)](https://github.com/simonpierreboucher02/llm_R_notebook-main/commits/main)

[![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)](https://www.r-project.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)](https://openai.com/)
[![Anthropic](https://img.shields.io/badge/Anthropic-000000?style=for-the-badge&logo=anthropic&logoColor=white)](https://www.anthropic.com/)
[![Cohere](https://img.shields.io/badge/Cohere-000000?style=for-the-badge&logo=cohere&logoColor=white)](https://cohere.ai/)
[![Mistral AI](https://img.shields.io/badge/Mistral%20AI-000000?style=for-the-badge&logo=mistralai&logoColor=white)](https://mistral.ai/)

[![Repository Size](https://img.shields.io/github/repo-size/simonpierreboucher02/llm_R_notebook-main)](https://github.com/simonpierreboucher02/llm_R_notebook-main)
[![Lines of Code](https://img.shields.io/tokei/lines/github/simonpierreboucher02/llm_R_notebook-main)](https://github.com/simonpierreboucher02/llm_R_notebook-main)
[![Code Language](https://img.shields.io/github/languages/top/simonpierreboucher02/llm_R_notebook-main)](https://github.com/simonpierreboucher02/llm_R_notebook-main)

---

This repository contains Jupyter notebooks that interact with various Large Language Model (LLM) APIs using the R programming language. It provides a structured approach to accessing Anthropic, Cohere, Mistral, and OpenAI APIs from R, enabling a range of NLP tasks such as text generation, retrieval-augmented generation, and conversation.

## 🚀 Features

- **Multi-API Support**: Integration with 4 major LLM providers
- **R Programming**: Native R implementation for data scientists
- **Jupyter Notebooks**: Interactive development environment
- **Comprehensive Examples**: Ready-to-use code snippets
- **Cross-Platform**: Works on Windows, macOS, and Linux

## 📁 Repository Structure

- **[R_ANTHROPIC_API.ipynb](https://github.com/simonpierreboucher02/llm_R_notebook-main/blob/main/R_ANTHROPIC_API.ipynb)**: Demonstrates how to set up and use Anthropic's API within an R notebook, including parameter configuration and API call examples.
- **[R_COHERE_API.ipynb](https://github.com/simonpierreboucher02/llm_R_notebook-main/blob/main/R_COHERE_API.ipynb)**: A notebook for interacting with Cohere's API in R, featuring examples for text generation and retrieval tasks.
- **[R_MISTRAL_API.ipynb](https://github.com/simonpierreboucher02/llm_R_notebook-main/blob/main/R_MISTRAL_API.ipynb)**: Explains how to connect with the Mistral API using R, showing examples for configuring requests and handling responses.
- **[R_OPENAI_API.ipynb](https://github.com/simonpierreboucher02/llm_R_notebook-main/blob/main/R_OPENAI_API.ipynb)**: Guides users through accessing the OpenAI API with R, covering setup, customization of parameters, and various example calls.

## 🛠️ Getting Started

### Prerequisites

To run these notebooks, you will need:
- **Jupyter Notebook with R kernel (IRkernel)**
- **R 4.0 or newer**
- API keys for each respective service (Anthropic, Cohere, Mistral, OpenAI)
- Required dependencies as listed in `requirements.txt`

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/simonpierreboucher02/llm_R_notebook-main.git
   cd llm_R_notebook-main
   ```

2. Install the dependencies for Jupyter Notebook and any Python API calls:

   ```bash
   pip install -r requirements.txt
   ```

3. **Install R Packages**: Open an R session or include these commands at the beginning of each notebook to install necessary R packages:

   ```R
   install.packages("httr")  # for API requests
   install.packages("jsonlite")  # for JSON parsing
   install.packages("tidyverse")  # for data manipulation if needed
   install.packages("reticulate")  # for Python interoperability if required
   ```

### Running the Notebooks

1. **Start Jupyter Notebook**: Open Jupyter with the R kernel by running:
   ```bash
   jupyter notebook
   ```
2. **Select a Notebook**: Open the notebook for the desired API provider (Anthropic, Cohere, Mistral, or OpenAI).
3. **Follow Instructions**: Each notebook includes specific instructions on authenticating, setting up, and making API requests in R.

## 💡 Use Cases

- **API Interactions**: Each notebook provides examples of API calls for generating text, performing retrieval, and other LLM tasks.
- **Parameter Configuration**: Customize parameters such as temperature, prompt structure, and token limits to fine-tune model responses.
- **Cross-Model Comparisons**: Enables testing and comparing outputs from different LLM providers within the R environment.

## 🤝 Contributing

We welcome contributions! Feel free to submit issues or pull requests to enhance functionality, add features, or address bugs.

[![Contributors](https://img.shields.io/github/contributors/simonpierreboucher02/llm_R_notebook-main)](https://github.com/simonpierreboucher02/llm_R_notebook-main/graphs/contributors)

## 📄 License

This repository is licensed under the MIT License.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 👨‍💻 Author

**Simon Pierre Boucher**
- GitHub: [@simonpierreboucher02](https://github.com/simonpierreboucher02)
- Repository: [llm_R_notebook-main](https://github.com/simonpierreboucher02/llm_R_notebook-main)

---

⭐ **Star this repository if you find it helpful!**

