# ibjjf_parser  
  
The International Brazilian Jiu-Jitsu Federation (IBJJF) is a for-profit company that hosts several of the biggest Brazilian jiu-jitsu tournaments in the world.  I love BJJ, actively compete in it, and have many teammates compete in these IBJJF events often. Some of these tournaments have 1000s of competitor entries. Using **BeautifulSoup, pandas, and openpyxl** libraries, I webscrape a list of my teammates into an Excel sheet where I will later figure out each individual competitor's mat assignment and time.  I added Excel conditional formatting via Python based on their current BJJ belt rank. Then I convert each person's name into a URL of their invdividual bracket in the Excel file. I will be able to use this scraper for future events to get a list of my teammates faster. We attend about 7 of these events per year. 
  
Once bouts are assigned, the time and mat assignment is dumped in, and then my team uses this list to stay organized as one big group at the event. I built this for my own personal use.      

# IBJJF Registration List
![IBJJF Screenshot](https://github.com/david125tran/ibjjf_parser/blob/main/images/IBJJF-athletes.png)  

# IBJJF Brackets with URL
![IBJJF Screenshot](https://github.com/david125tran/ibjjf_parser/blob/main/images/brackets.png)  

# Intermediary Result (Excel File with Names, Color Coded Rank, Division, and Hyperlinks to Brackets):
![Excel Screenshot](https://github.com/david125tran/ibjjf_parser/blob/main/images/brackets-part-2.png)  
  
# End result:  
![Excel Screenshot](https://github.com/david125tran/ibjjf_parser/blob/main/images/brackets-part-3.png)  
