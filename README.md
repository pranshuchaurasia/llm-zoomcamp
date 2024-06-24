
# LLM Zoomcamp

## Project Description
This repository contains the materials and code for the LLM Zoomcamp organized by Datatalks Club. It includes introductory tutorials and exercises to help learners understand and implement large language models effectively.

## Installation
To set up the project environment, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/llm-zoomcamp.git
   ```
2. Navigate to the project directory:
   ```
   cd llm-zoomcamp
   ```
3. Create and activate a virtual environment:
   ```bash
   python -m venv llm-zoomcamp
   .\llm-zoomcamp\Scripts\Activate.ps1  # On Windows
   source llm-zoomcamp/bin/activate  # On Unix or MacOS
   ```
4. Install the required Python packages:
   ```
   pip install -r requirements.txt
   ```
5. Create a `.env` file in the root directory with necessary configurations (API keys, environment settings, etc.). See the Environment Variables section below for details.


## Usage
Navigate to the `01-intro` directory to start with the introductory lessons:

```
cd 01-intro
```

Here, you can find Jupyter notebooks that you can run to see examples of large language models in action.

## File Documentation
### `01-intro` Directory
- **OpenAI_Practice.ipynb**: Demonstrations of OpenAI model interactions.
- **documents.json**: Data used in the notebooks for loading and manipulation.
- **minsearch.py**: Python script for a minimal search algorithm demonstration.
- **parse-faq.ipynb**: Techniques for parsing FAQs and extracting information.
- **rag-intro.ipynb**: Introduction to Retrieval-Augmented Generation.

## Environment Variables
To run the project, you need to set up environment variables that the application can use:
1. Create a `.env` file in the project root directory.
2. Add variables like `API_KEY="your_api_key_here"`.
3. Ensure the application reads these variables at runtime.

## Contributing
Contributions are welcome! If you have improvements or corrections to propose, please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Thanks to Datatalks Club for organizing this educational initiative.
