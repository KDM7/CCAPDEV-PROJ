# CCAPDEV-PROJECT
Set up
Step 1
Download files from github repository (https://github.com/KDM7/CCAPDEV-PROJ.git)
Step 2
Download node modules (https://drive.google.com/drive/folders/1H4cDDIIc0_4G357VA916Ak_6rD1qZWJn?usp=sharing)
Step 3
Install node modules
    Rename the downloaded folder to "node_modules"
    Copy the folder to C:\Users\"Your username on your pc"\AppData\Roaming\npm
    Replace the node_module file if ever there is one
Step 4
Download env file (https://drive.google.com/drive/folders/1dl2vqTmwbVseGhVAUqDJXtkBxSWVpBeA?usp=sharing)
Step 5
Integrate env file
    Rename downloaded file to ".env"
    Copy and paste file onto project folder
Step 6
Run the application
    Open project folder on the command prompt
    Type "npx nodemon"
    go to a browser and type "http://localhost:3000/"

Logging in
Step 1
Open the model folder in the project folder
Step 2
Open Sample Data then select Users.json
Step 3
Copy Credentials
    Note
    Users 1 - 36 are employees
    Users 37 - 42 are customers
Step 4
Input credentials onto the login page

Additional notes
I was not able to utilize bcrypt
I was not able to let the user edit their own comments
I did not let employees comment on their own restaurants or view comments of other restaurants (this was intentional)
I was not able to let the customers remove items from the cart