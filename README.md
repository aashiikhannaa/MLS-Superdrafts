# MLS-Superdrafts
To anyone who desires to get drafted in Major League Soccer through college and wants help in university shortlisting, this repo is for you.

### Methodology :

1. I web-scraped Wikipedia pages to get the MLS Superdrafts from 2024 to 2014 (Last 10 years)
(Eg.: https://en.wikipedia.org/wiki/2020_MLS_SuperDraft for 2020)
2. My target column was 'College', so in every page I found the tables which had that column, thus discarding irrelevant columns.
3. I created a dataframe, and added the Colleges for every year, column by column.
4. Renamed each column to denote the year.

Note: I tried multiple other methods like scraping first, then copying only "College" column one-by-one to a dataframe. It didn't seem to work, since the length of the dataframe was restricted to the length of the first column. Hence, concatenation helps.

I also went on to visualise since data speaks best when visualized!
1. Top 20 Colleges for MLS Drafting since 10 years
2. Top Colleges Drafted Post COVID

Libraries - BeautifulSoup, Pandas, Requests

Thus, even if you are a layman, you now know the stats about the colleges which produce the most MLS drafts.

P.S. - I did this little project to help my friend to shortlist his undergrad universities based of MLS drafting.

All the best!
