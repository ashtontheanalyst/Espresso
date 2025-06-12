# Espresso Tracker

**This [espresso tracker](https://docs.google.com/spreadsheets/d/1QKe35mxrdCpQ37INgrker8umBf5o3EsWHfDWStIRg2s/edit?usp=sharing) is to be used for keeping
a log of the shots pulled from my Breville Bambino.**  
It's also a personal project using python, jupetyer notebook, pandas, matplotlib, and etc.

![Alt Text](./assets/pour.gif)

# Helpful Instructions
The Google Sheet tracking my shots is not open for edits from anyone but myself, but you're welcome to view it [here](https://docs.google.com/spreadsheets/d/1QKe35mxrdCpQ37INgrker8umBf5o3EsWHfDWStIRg2s/edit?usp=sharing)! If you were to recreate this project one-for-one, then you'd need to make a google sheet like it and change some of the import variables within `tracker.ipynb`.

## Our Virtual Environment
- Creating:
    ```sh
    python -m venv myenv
    ```

- Starting:
    - Windows:
        ```sh
        myenv\Scripts\activate
        ```
    - Linux:
        ```sh
        source myenv/bin/activate
        ```

- First Start/Requirements:
    ```sh
    pip install -r assets/requirements.txt
    python -m ipykernel install --user --name=myenv --display-name "Python (myenv)"
    ```

- Closing:
    - Windows:
        ```sh
        myenv\Scripts\deactivate.bat
        ```
    - Linux:
        ```sh
        deactivate
        ```

## Configuring Jupyter Notebook in VS Code
- Open VSCode and go to your `something.ipynb` file, then enter 'Ctrl + Shift + P'
- Then search 'Python: Select Environment'
- First, if you see `(myenv)` just click on that and be done, or...
- Click 'Enter interpreter path...' and then 'Find...'
- It'll pop up your file system, select the virtual env folder (in this case it's named `/myenv`)
- Navigate to `/Scripts` (on windows) or `/bin` (on Linux) within `/myenv`
- Select the executable python file
- For the **python kernel**, pick the virtual env