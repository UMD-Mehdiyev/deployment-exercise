# Random Quote Generator 
This is a Python-based application that fetches and displays random quotes from an online API. It includes a GUI with functionality to retrieve a new quote and an option to read the quote aloud using text-to-speech. 

## Instructions for Self-Deployment / Setup 

### Step 1: Clone the Repository 
First, clone the repository to your local machine: 
``` 
git clone https://github.com/UMD-Mehdiyev/deployment-exercise.git 
cd deployment-exercise 
``` 

### Step 2: Install Dependencies 
Use the following commands to install required libraries. 

#### Windows: 
``` 
pip install -r requirements.txt 
``` 

#### macOS (with Homebrew installed): 
``` 
python3 -m pip install -r requirements.txt 
``` 

#### Linux: 
``` 
sudo apt-get update && sudo apt-get install 
python3-pip -y pip3 install -r requirements.txt 
``` 
> [!NOTE] 
> Note: If pip is not recognized, try python3 -m pip install -r requirements.txt or pip3 install. 

### Step 3: Run the Application 
Start the app with: 
``` 
python app.py 
``` 
The GUI should open, allowing you to fetch quotes and hear them read aloud. 


### Troubleshooting 
If you encounter issues, try these solutions: 
- Dependency Errors: Make sure all libraries are installed. Run `pip list` to verify. 
- Text-to-Speech Issues: Ensure `gTTS` is installed and properly configured.