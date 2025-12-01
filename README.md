# Lesson on cardio-respiratory physiology: theory and practice

By Valentin Ghibaudo

## Outline
  * Theory : **cardio_respi_lesson_theory.pdf** 
  * Practice : **cardio_respi_lesson_practice.pdf** and **cardio_respi_lesson_practice.ipynb** 

## Installing Python with **uv**
1. On macOS and Linux. Open a terminal and do
   `$ curl -LsSf https://astral.sh/uv/install.sh | sh`
1. On windows. Open a terminal using **CMD** in the windows menu and do
   `powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"`
2. Exit the terminal and open it again.
3. Download with right click and save this file corresponding in "Documents" folder:
    * [`requirements.txt`](https://raw.githubusercontent.com/ValentinGhibaudo/Formation_2025_physio_cardio_respi/main/requirements_physio.txt)
4. open terminal or **CMD**
5. `uv venv env_formation_physio --python 3.12`
6. For Mac/Linux `source env_formation_physio/bin/activate` (you should have `(env_formation)` in your terminal) or for Powershell `env_formation_physio\Scripts\activate`
7. `uv pip install -r Documents/requirements_physio.txt`