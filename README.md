This project was part of the course Secure AI for News Investigations. The assignment guide was to replicate techniques shown in the AI course to better handle large data sets.
For this assignment, I used scraped tabular data from [Washington's OAG]'s Data Breach Notifications Directory (https://www.atg.wa.gov/data-breach-notifications?page=0) and tokenized all compromised information. Then I put it into a dataframe that summarized what was compromised per company.
This project revealed that many Washington residents had their data exposed by repeat companies. I also saw the most common form of exposed information and who had the most information exposed in a leak.

Some companies with several data leaks in recent years: 
Seattle Housing Authority                   3
Premera Blue Cross                          3
Rite Aid Corporation                        3
Maximus, Inc.                               3
Fred Hutchinson Cancer Center               3


Some companies with the most information (tokens) exposed:
TD Ameritrade, Inc. and Charles Schwab & Co., Inc.
Kirkland & Ellis LLP
Henry Schein, Inc.
Washington Department of Labor & Industries
Americold Realty Trust

This story could develop further in two ways: 
      1. Focus on companies that have repeatedly exposed user data, looking for patterns of negligence and/or vulnerability. Do some of these companies use less secure platforms that more easily expose data (e.g., patient information)? And how did they deal with significant breaches - did they do/change anything?
      2. Highlight the types of information most commonly exposed (e.g., social security numbers, names, DOB) and the potential risks to individuals. Were affected groups victims of identity fraud? Or did the leaks make them vulnerable to dark/deep information markets?

This story also has the potential to grow and compare Washington's leaks to other states. The only difference would be that not every state releases information about data compromises.
