# GitHub Repository Visualization with Language Selection

This Python script utilizes the GitHub API and Plotly Express to create an interactive bar chart that displays information about the most-starred GitHub repositories based on a user-selected programming language. Users can choose a programming language from a dropdown menu, and the script retrieves repository data and generates a visualization accordingly.

## Prerequisites

- Python 3.x
- Required Python packages: `requests`, `plotly`, `ipywidgets`

## Installation

1. Clone or download this repository.

    ```bash
    git clone https://github.com/hharpreetk/github-repo-data-viz.git
    cd github-repo-data-viz
    ```

2. Install the required packages.


3. If you are using Visual Studio Code (VSCode) and plan to use IPython widgets, you'll also need to install the `ipykernel` package to enable widget functionality. To do this, follow these steps:

- Open VSCode.
- Make sure you have the Python interpreter configured (you should see the selected Python version at the bottom of the VSCode window).
- Open a terminal within VSCode.
- Run the following command to install `ipykernel`:

  ```bash
  pip install ipykernel
  ```

## Usage

1. Open the github_pop_repo_viz.ipynb Jupyter Notebook.

2. Run the notebook cells to execute the code.

3. A dropdown menu will appear, allowing you to select a programming language.

4. Based on your selection, the script will make an API call to retrieve GitHub repository data for the selected language and create an interactive bar chart visualization using Plotly Express.

5. Interact with the chart to explore the most-starred repositories for the chosen programming language.

## Customization
- You can add more programming languages to the options list in the language_dropdown widget.

- Modify the color_palette list to change the color scheme of the bar chart bars.

- Adjust the layout and styling of the visualization in the code to suit your preferences.

## Credits
- GitHub API: GitHub Developer API
- Plotly Express: Plotly
- IPython Widgets: ipywidgets

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
