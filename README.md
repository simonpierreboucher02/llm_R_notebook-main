# LLM R Notebook

This repository contains Jupyter notebooks that interact with various Large Language Model (LLM) APIs using the R programming language. It provides a structured approach to accessing Anthropic, Cohere, Mistral, and OpenAI APIs from R, enabling a range of NLP tasks such as text generation, retrieval-augmented generation, and conversation.

## Repository Structure

- **[R_ANTHROPIC_API.ipynb](https://github.com/simonpierreboucher/llm_R_notebook/blob/main/R_ANTHROPIC_API.ipynb)**: Demonstrates how to set up and use Anthropic's API within an R notebook, including parameter configuration and API call examples.
- **[R_COHERE_API.ipynb](https://github.com/simonpierreboucher/llm_R_notebook/blob/main/R_COHERE_API.ipynb)**: A notebook for interacting with Cohere's API in R, featuring examples for text generation and retrieval tasks.
- **[R_MISTRAL_API.ipynb](https://github.com/simonpierreboucher/llm_R_notebook/blob/main/R_MISTRAL_API.ipynb)**: Explains how to connect with the Mistral API using R, showing examples for configuring requests and handling responses.
- **[R_OPENAI_API.ipynb](https://github.com/simonpierreboucher/llm_R_notebook/blob/main/R_OPENAI_API.ipynb)**: Guides users through accessing the OpenAI API with R, covering setup, customization of parameters, and various example calls.

## Getting Started

### Prerequisites

To run these notebooks, you will need:
- **Jupyter Notebook with R kernel (IRkernel)**
- **R 4.0 or newer**
- API keys for each respective service (Anthropic, Cohere, Mistral, OpenAI)
- Required dependencies as listed in `requirements.txt`

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/simonpierreboucher/llm_R_notebook.git
   cd llm_R_notebook
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

## Use Cases

- **API Interactions**: Each notebook provides examples of API calls for generating text, performing retrieval, and other LLM tasks.
- **Parameter Configuration**: Customize parameters such as temperature, prompt structure, and token limits to fine-tune model responses.
- **Cross-Model Comparisons**: Enables testing and comparing outputs from different LLM providers within the R environment.

## Contributing

We welcome contributions! Feel free to submit issues or pull requests to enhance functionality, add features, or address bugs.

## License

This repository is licensed under the MIT License.

