<b>SPENDING DATA</b>
Issues:
1. According to database installation <a href="https://files.usaspending.gov/database_download/usaspending-db-setup.pdf">instructions</a>, 50 Gb needed locally for installation. After clearing space on my local hard drive, I now have nearly 200 Gb (of 500 Gb) free. When I tried to unzip the 46 Gb file that I downloaded, I received the following error message.<br>
<img src="Spending_database_error.png">
2. The instructions also state that 1 TB is needed "to store the fully restored database." This seems to imply that I will need to run the spending data from an Amazon cluster.<br>
3. I have reviewed the data dictionary for the spending data, but do not yet understand this well enough to have determined how I will segment this data.<br><br>
<b>VOTING DATA</b><br>
I have manually cleaned the voting data for 2016 and 2014. I am about 2/3 complete with the manual cleaning of the 2012 vote counts. Electoral features that I intend to analyze include:<br>
1. How many candidates ran for each congressional seat?<br>
2. What was the % margin of victory?<br>
3. What is the average number of votes cast for each seat? (I plan to use this as a proxy for the number of constituents represented.)
