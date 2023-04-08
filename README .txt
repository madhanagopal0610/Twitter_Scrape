README :

	This is a Python script that uses the snscrape library to scrape tweets from Twitter based on a keyword or hashtag, start date, and end date. It also saves the scraped data to a MongoDB database.

	To use this script, you will need to have Python installed on your computer, as well as the following libraries:	
			1.snscrape
			2.pandas
			3.streamlit
			4.base64
			5.pyamongo
		

	You can install these libraries using pip:
		pip install snscrape pandas streamlit pymongo 
	
	Once you have installed the necessary libraries, you can run the script using the following command:
		python script_name.py 

	When you run the script, a Streamlit app will open in your web browser. You can enter a keyword or hashtag, start date, and end date, and then click the "Scrape" button to start scraping tweets. The scraped data will be displayed in a table, and you can download it as a CSV or JSON file by clicking the corresponding button.
You can also view the saved data by clicking the "View Saved Data" button. This will display all of the data that has been saved to the MongoDB database.

