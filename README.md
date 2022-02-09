## Generalized Yield Curve Script
This generalized yield curve script is intended to take a users two columns of interested, historically spend and the main KPI of interest, and create a visual and regression summary. The results of the yield curve script will be saved locally in a user specified directory. 

### Getting Started
To run the script, the user needs to take a few steps to get started:
1. Ensure the data is saved in an excel file, with one tab
2. The column names are _one word, with no spaces or special characters_
3. The columns in the data file are the same length

Once this prework is done, the user then needs to:
1. Specify the file path:
- Click on the file in your local directory
- Click on "Home" in your file explorer
- Click "Copy Path"
2. After this, the user then needs to create a local folder for the output to be stored, and follow the same steps as above

### Running the Script
Once the above is completed, the user only needs to make three changes:
1. Paste the raw data path onto the `rawData_path` variable </br>
2. Paste the output folder onto the `output_path` variable </br>
3. Create a new cell in the notebook and call the function `yield_curves` function with the arguments being the name of the x variable, and the y variable, _in that order_

### Expected Output
Following the conclusion of the script, the user will see:
1. A text file of regression results saved in their local directory
2. The visual saved in the same folder

Note the function will also print the regression results and visual in the same folder

### Misc
For education purposes, I've included dummy data on in this folder for MAI users to test the script on
