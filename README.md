# Twitter-Analysis

**Goal:**
- The goal of this project was to successfully collect data from a website using BeautifulSoup API, and perform ETL(Extract, Transform, and Load) to create newly processed data, and I wanted to figure out if there were any correlations between the number of followers and average likes by analyzing Twitter's top 200 users with the most followers. 

**Used APIs links:**
- BeautifulSoup: https://beautiful-soup-4.readthedocs.io/en/latest/
- Pandas: https://pandas.pydata.org/docs/
- NumPy/Scipy: https://docs.scipy.org/doc/
- Matplotlib: https://matplotlib.org/stable/index.html

**Data website:**
- Viral Pitch: Top 200 Most Followed Twitter Accounts in 2023
- https://viralpitch.co/topinfluencers/twitter/top-200-twitter-influencers/

**Data attributes and Data type:**
- rank: int.
- twitterName: string
- type: string
- posts: int. (in thousands)
- followers: int. (in millions)
- avg. likes: int. (in thousands, except the 1's)

**Issues:**
- 1k and 1 for average likes will come up as the same, so to fix it I would make the 1's to come up as 0, as misinput.
