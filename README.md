# ODSC West 2024


## Contents

- **Notebooks**:
  - `catboost/catboost.ipynb`: "Slides" for Catboost
  - `polars/Idiomatic Polars.ipynb` : "Slides" for Polars
- **Environment Setup**: Instructions for running these notebooks in various environments (locally, Codespaces, and Google Colab).

## Running the Jupyter Notebooks

You can run the notebooks in several ways, depending on your preferences and setup:

### 1. Running Locally

To run the notebooks locally, you will need to create a virtual environment and install the necessary dependencies.

1. Clone the repository:
   ```sh
   git clone git@github.com:mattharrison/odsc_west_2024.git
   cd odsc_west_2024
   ```

2. Set up the environment using `uv`:

   Mac/Linux:
   ```sh
   $ curl -LsSf https://astral.sh/uv/install.sh | sh
   ```
   Windows:
   ```cmd
   > powershell -c "irm https://astral.sh/uv/install.ps1 | iex"
   ```

   Then run:
   ```
   uv sync
   ```

   The above commands will create a virtual environment, activate it, and install dependencies.

3. Start Jupyter Notebook:
   ```sh
   uv run jupyter notebook
   ```

### 2. Running on GitHub Codespaces

GitHub Codespaces allows you to run this project entirely in the cloud without needing to set up a local environment.

1. Open the GitHub repository in your browser.
2. Click the **Code** button and select **Open with Codespaces**.
3. After the Codespace launches, wait for it to install the environment.
4. Click on the notebook and select the local kernel.

The project is pre-configured to install the necessary dependencies when the Codespace is first created.

### 3. Running on Google Colab

You can also run the notebooks on Google Colab, which provides free GPU/TPU resources for faster computations.

1. Open the repository on GitHub.
2. Navigate to the desired Jupyter notebook file (ending in `.ipynb`).
3. Update the domain from `github.com` to `githubtocolab.com`
4. Once in Colab, you may need to run the first cell to install any required dependencies.

## Dependencies


To see the complete list of dependencies, please check the `pyproject.toml` file.

## Suggested Reading

To deepen your understanding of Python for data analysis, we recommend the following books:

- [*Learning Python for Data*](https://store.metasnake.com/learningpy): This book provides a comprehensive introduction to Python, with a focus on its applications in data analysis. It covers Python fundamentals, essential libraries, and practical examples to help you get started with data-driven projects.

- [*Effective Polars*](https://store.metasnake.com/a5018258-063b-4802-b395-34e75b6eeb5e): A guide to mastering data manipulation and analysis with Polars.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request if you have suggestions, improvements, or additional notebooks to add.

## License

This project is licensed under the MIT License.

## Contact

If you have any questions, feel free to reach out or open an issue on the repository.

