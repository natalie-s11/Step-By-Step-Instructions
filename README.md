# Step-By-Step-Instructions
Step by Step Recipe for Creating a New Working Project Environment

1. Fork the Repository
- Click "Fork"
- Click "Create Fork"

2. Open it as a Codespace
- Click "Code"
- Click "Codespace"
- Click the + sign
- Go back to the previous page and click the three dots next to the new Codespace name and click Open in Visual Studio Code

3. Add a new .py file
- Under the explorer side tab, click the New File button and name the file, make sure it ends in .py.
- Type "#%%" to add section breaks and make the .py file interactive

4. Set up the virtual environment
- Go into the terminal and type: python -m venv .venv
- Then type: source .venv/bin/activate

5. Requirements.txt file
- Check whether a requirements.txt file already exists by typing in the terminal: ls
- If it exists, install the dependencies by typing: pip install -r requirements.txt
- If the file does not exist, create it after installing required packages by running: pip freeze > requirements.txt
- Then, when new packages are added, install them first: pip install <package>
- Update the requirements file to reflect the current environment: pip freeze > requirements.txt

6. Push all changes to GitHub
- In the terminal type: git status
- Then: git add .
- Then: git commit -m "Update environment, requirements, and project files"
- Then: git push origin main

7. Refresh your GitHub repository to see the changes


  

