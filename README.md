# RL-Maze

Standard SARSA Control and Tabular Dyna-Q are used to solve for a solution for a given maze.

To run the algorithm:
- Download the necessary packages
  - `$ pip install -r requirements.txt`
- Download the [Chrome WebDriver](https://chromedriver.chromium.org/downloads) for your version of Google Chrome
  - *Note: You can find your current version of Google Chrome by clicking the three dots in the top right &#8594; "Help" &#8594; "About Google Chrome"*
- Copy the path where the Chrome WebDriver was downloaded and set to a variable called `PATH` in the Jupyter Notebook
  - Example: `PATH = 'D:\Program Files (x86)\chromedriver.exe'`
- Copy the path of the `maze` directory in your local copy of this repository and set to a variable called `DOWNLOAD_PATH` in the Jupyter Notebook
  - This will be the location where the image of the maze will be downloaded 
  - Example: `DOWNLOAD_PATH = 'D:\Github\Work\RL-Maze\maze'`
- Run the Jupyter Notebook
