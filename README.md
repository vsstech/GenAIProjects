# Setup instructions (mac)

## Environment setup
  a. Clone repo 
  
   ```bash 
     git clone https://github.com/vsstech/llm_projects
   ```
  			
  b. Open a new Terminal (Applications > Utilities > Terminal)
     Run python --version to find out which python you're on. Ideally you'd be using a version of Python 3.11
     You can download python here:
     https://www.python.org/downloads/

  c. Navigate to the "project root directory" using cd ~/Documents/Projects/llm_projects (replace this path with the actual path to the llm_projects 
     directory, your locally cloned version of the repo). 
     Then, create a new virtual environment with this command:
	 
  ```bash 
     python -m venv llme
  ```
	
   Activate the virtual environment with
	
  ```bash 
    source llme/bin/activate 
  ```

   You should see (llms) in your command prompt, which is your sign that things are going well. Run below dommand
  
  ```bash
	pip install -r requirements.txt
  ```
  This may take a few minutes to install.

   d. Start Jupyter Lab:

   From within the llm_projects folder, type: 
   ```bash 
     jupyter lab
   ```
  and Jupyter Lab should open up, ready for you to get started			

## Install Local Light weight LLM Ollama 

Visit ollama.com and install!
Once complete, the ollama server should already be running locally.
If you visit: http://localhost:11434/
You should see the message Ollama is running.
