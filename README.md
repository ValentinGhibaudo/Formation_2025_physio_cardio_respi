# Lesson on cardio-respiratory physiology: theory and practice

By Valentin Ghibaudo

## Theory
* Read : **./slides/cardio_respi_lesson_theory.pdf**

## Practice
### Download ZIP file
  * Downlaod ZIP file (green CODE button -> Download ZIP), store it where you want and unzip it.

### Installing Python with **uv** in 7 steps
1. Install **uv** On macOS and Linux. Open a terminal and do
   `$ curl -LsSf https://astral.sh/uv/install.sh | sh`
1. Install **uv** on windows : Open a terminal using **CMD** in the windows menu and run
   `powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"`
2. Exit the terminal and open it again.
3. Download with right click and save this file corresponding in "Documents" folder:
    * [`requirements_physio.txt`](https://raw.githubusercontent.com/ValentinGhibaudo/Formation_2025_physio_cardio_respi/main/requirements_physio.txt)
4. Open terminal (or a **CMD**)
5. Run it to install a Python 3.12 environment named env_formation_physio : `uv venv env_formation_physio --python 3.12`
6. Run it to activate your environment : For Mac/Linux `source env_formation_physio/bin/activate` (you should have `(env_formation_physio)` in your terminal) or for Powershell (windows) run  `env_formation_physio\Scripts\activate`
8. Run it to install Python libraries : `uv pip install -r Documents/requirements_physio.txt`

### Running an example notebook
  * Open a terminal and activate the environment (cf .6)
  * Run it to start a JupyterLab session in your web browser : jupyter-lab
  * With the explorer of jupyterlab, go to to the "notebooks" folder of the unzipped downloaded folder
  * Double click on the **cardio_respi_lesson_physio_practice.ipynb** to open it. Run it cell by cell with shift + enter or with the double-arrow button to run all the cells at once.