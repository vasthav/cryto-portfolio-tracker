# cryto-portfolio-tracker
A simple crypto currency portfolio management spreadsheet and tracker using Google sheet and App Script.

### How to Install/Setup?
1. Go to [Google Sheets](https://docs.google.com/spreadsheets/u/0/) and create a new blank spreadsheet.
2. Go to FILE > Import > Upload and select the crypto Tracker.xlsx file from the repo. And once uploaded select replace spreadsheet.
3. Once imported go to TOOLS > Script Editor and replace the code with the contents of app-script.txt found in the repository.
4. Give permission to the script if prompted.
5. Select the function "MyFunction" from the dropdown menu and click on play icon to run the script.
6. You can also run the script by going to RUN > Run Function > Myfunction from the menu. 
7 Go to the spread sheet and see the values updated.

### How to use?
There are two sections to the spreadsheet.
a. Portfolio Tracker
b. Market Watch

#### Portfolio Tracker
This is to keep track of your present cryptocurrency portfolio and the profit loss in both USD and INR
To use the portfolio tracker just fill in the feilds 4 feilds
- Ticker	
- Exchange 
- Quantity
- Buy price
Once filled go and run the app script as mentioned above. And the Values will be automatically updated.

#### Market Watch 
This keeps track of the potential cryptocurrency and their performance on different durations.
To use the portfolio just fill in the 'Ticker' field and the app script.

### Automatic updation of sheet
This can be achieved using triggers in app script.
1. Go to EDIT > Current Projects Triggers. It opens the G Suite Developer Hub. 
2. Click on 'Add trigger' available at the right bottom of the page.
3. Select the required options and Save.

# LICENSE
check the Licence file.
