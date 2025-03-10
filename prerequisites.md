# Prerequisites 

Please complete the steps below prior to the ClePy-PyLadies meeting on March 11 if you would like to follow along with the group activity.

## Install Python

1. Go to https://www.python.org/downloads/
2. Click the Download Python button
3. Follow the instructions in the installer

## Install Ollama

1. Go to https://ollama.com/download
2. Select your operating system
3. Click the Download button
4. Follow the instructions in the installer

## Download the tinyllama language model

1. Open a command prompt
2. Run the command `ollama pull tinyllama`

## Download Python dependencies

1. Open a command prompt
2. Run the command `git clone https://github.com/eddie-cosma/clepy-ollama.git`
3. Enter the new directory with `cd clepy-ollama`
4. Create a virtual environment with `python3 -m venv .venv`
5. Activate the virtual environment with `.venv\Scripts\activate.bat` (Windows) or `source .venv/bin/activate` (Mac/Linux)
6. Install dependencies using `pip install -r requirements.txt`

