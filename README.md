# Linkedin_Profile_AnalysisLinkedIn Profile Data Analysis using Power BI
# Steps Involved In the Project :-
# 1) Data Extraction And Exploration 🔍
- The data used in this project was extracted from LinkedIn itself. You Can also extract your profile data from LinkedIn by (LinkedIn - > Settings and Privacy -> Data Privacy -> Get a Copy of your Data)
- After the data was extracted, I loaded it into my PowerBI. I came to know that all the different tables such as connections, social activities, and companies were present and had date columns but needed a common date table to change accordingly. So, to solve that we need to go to the next stage which is Data Transformation.

# 2) Data Transformation ⚒️
- It was seen that some of the tables such as “companies” had different date formats than that of “connections”. So, the 1st step of the data transformation I did was to convert all the dates columns of all the tables into one format (DD-MM-YYYY).
- Next step was to create a Custom Calendar Table using Power Query. The new calendar table contains a date column with all the dates in (DD-MM-YYYY).

# 3) Building Relation Between the Tables 🤝
- After the creation of the Custom Calendar table the Date column of Custom Calendar was Joined with the Date column of other tables.
- That is all the tables were now related to the Custom Calendar table. So that we can apply filters to the data concerning the date.

# 4) Final Dashboard 📊
- Finally started building the Dashboard.
- The Dashboard contains 3 pages: -
1.Home Page
2.Profile Analysis
3.Connection Analysis
    
# 5) Publishing the Dashboard 📰
- This is the last stage where I published my Dashboard from the PowerBI desktop to the PowerBI cloud.

# Insights
- Total Number Of Connections across the years 2022,2023 and 2024 is 250
- Highest Number of connections happend in the year 2024 i.e 226
- Total connections by month june is high i.e 110
- Total Number of Connection Invitations(sent and received) is 307
- All the connections invitations were seen in 2024
- Total Number of companies followed by me is 17
- Total Number of Reaction till now is 57
- Number of posts is 1
- Total Number of Messages(sent and received) is 20
- Total Number of Messages sent is 20(67% of total)
- Total Number of Messages Received is 10(33% of total)
