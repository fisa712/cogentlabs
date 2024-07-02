# Study Plan Generation using LangChain 🦜🔗

This project generates personalized study plans for students using LangChain and OpenAI's GPT-4 model.

## Table of Contents
- [Installation](#installation)
- [Environment Variables](#environment-variables)
- [Usage](#usage)
- [Tasks](#tasks)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/fisa712/cogentlabs.git
    cd cogentlabs
    ```

2. **Create a virtual environment:**

    ```bash
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. **Install the dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

## Environment Variables

Create a `.env` file in the root directory of the project and add your OpenAI API key:


## Usage

To run the notebook and generate a study plan:

1. **Open the Jupyter notebook:**

    ```bash
    jupyter notebook UntitledCogent.ipynb
    ```

2. **Run all cells in the notebook:**
    - Follow the instructions in the notebook to input student information.
    - The notebook will generate a personalized study plan based on the provided information.

## Tasks

### Generate Study Plan

1. **Load Dependencies:**
    Ensure all required libraries are imported.

2. **Set Up Environment Variables:**
    Load your API key from the `.env` file.

3. **Initialize Model:**
    Set up the OpenAI model with your API key.

4. **Define Prompt Template:**
    Create a prompt template for generating the study plan.

5. **Generate Study Plan:**
    Invoke the chain to generate a study plan.
### Generate summary of book
1. **using runnables created summary of the book**
   use langchain lcel runnables to get the summary of documents.
2. **utilizing reportlab to generate a pdf document**
     Use `reportlab` to create a PDF of the generated plan.
## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.
