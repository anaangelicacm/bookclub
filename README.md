# Book Club
![susan-q-yin-2JIvboGLeho-unsplash.jpg](https://github.com/anaangelicacm/booklub/blob/main/images/susan-q-yin-2JIvboGLeho-unsplash.jpg?raw=true)


## 1. Business Problem
Book Club is a book exchange startup. The business model works based on the exchange of books by users, each book registered by the user, gives the right to an exchange, but the user can also buy the book, if the user does not want to offer another book in exchange.

One of the most important tools for this business model to be profitable is the recommendation. An excellent recommendation increases the volume of exchanges and sales on the site. However, Book Club does not collect or store the books submitted by users.

Books for exchange are uploaded by users themselves through a button "Upload", they are visible on the site, along with their stars, which represent how much users liked the book or not. However, the company does not collect or store this data in a database.

Therefore, data must be collected directly from the company's website and stored in a database for consultation.

## 2. Business Assumptions
For this company the data is important to improve the book recommendation. However, the company doesn't collect the data to process and implement data for analysis or data science projects.

A recommendation system can facilitate recommending books for sale or for exchange. This can facilitate a greater number of visits within the site, and in this way create a greater number of visitors. That's why it is important to have constant data collection for analysis and creation of data science projects.

## 3. Solution Strategy
- **Step 1. Data collect:** Web scraping done on the [Books to Scrape ](https://books.toscrape.com);
- **Step 2: Data cleaning:** This step consisted of cleaning the data so that it could be stored properly;
- **Step 3: Database:** Save clean data to a relational database.

## 4. Conclusions


## 5. Lessons Learned
- Creation of ETL scripts;
- Extraction of site data using the BeautifulSoup library;
- Data manipulation tools: Pandas;
- Creation of tables in SQLite3 database.

## 6. Next Steps to Improve
- Creation of a recommendation system with the collected data.
