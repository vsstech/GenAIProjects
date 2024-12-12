Setup instructions (mac)


1. 
  a. Clone repo 
  			git clone https://github.com/vsstech/vss_llm_engineering
  b.Open a new Terminal (Applications > Utilities > Terminal)
     Run python --version to find out which python you're on. Ideally you'd be using a version of Python 3.11
     You can download python here:
     https://www.python.org/downloads/

  c.Navigate to the "project root directory" using cd ~/Documents/Projects/vss_llm_engineering (replace this path with the actual path to the llm_engineering directory, your locally cloned version of the repo). Do ls and check you can see subdirectories for each week of the course.
     Then, create a new virtual environment with this command:
     python -m venv llme

    Activate the virtual environment with
    source llme/bin/activate You should see (llms) in your command prompt, which is your sign that things are going well.

    Run pip install -r requirements.txt
    This may take a few minutes to install.

   d.Start Jupyter Lab:

      From within the vss_llm_engineering folder, type: jupyter lab
       ...and Jupyter Lab should open up, ready for you to get started			

2. Install Local Light weight LLM Ollama 
Simply visit ollama.com and install!

Once complete, the ollama server should already be running locally.
If you visit:
http://localhost:11434/

You should see the message Ollama is running.