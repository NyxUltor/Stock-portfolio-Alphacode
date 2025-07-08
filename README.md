# Stock portfolio-Task 2 for Alphacode Internsip
This project has been made for and in accordance of the task-2 as in the Alphacode internship
It is a simple stock tracker that calculates total investment based on manually defined stoack prices,below I shall again present the Goal,simplified scope and concepts to be used in this project as per the task list:

● Goal: Build a simple stock tracker that calculates total investment based on manually defined stock prices .

● Simplified Scope: 
○ User inputs stock names and quantity. 
○ Use a hardcoded dictionary to define stock prices (e.g., {"AAPL": 180, "TSLA": 250}). 
○ Display total investment value and optionally save the result in a .txt or .csv file. 

● Key Concepts Used: dictionary, input/output, basic arithmetic, file handling 
(optional).

Extra features:
Buy/Sell Support-
- Users can input negative quantities to sell stocks, not just buy
- Mimics real-world trading behavior

Oversell Protection-
- Prevents users from selling more shares than they currently own
- Ensures logical consistency in the portfolio

Real-Time Portfolio Tracking-
- After each transaction, shows the remaining shares of the stock
- Keeps users informed of their current holdings

Boolean Logic for Save Decision-
- Uses a Boolean variable (save_summary) to simplify yes/no logic
- Cleaner, more readable

File Format Choice with Validation-
- Lets the user choose between .txt and .csv format
- Validates input so the program doesn’t crash on invalid file types
