- With a Personal Access Token for GitHub API, implemented paginated requests to scrape the details of all users in Stockholm, with 100+ followers, and their 500 most recent repositories. Effectively managed rate limits by introducing 3-second delay between requests and monitoring "X-RateLimit-Remaining" header.
  
- From analysis, JavaScript (JS) is the most used language in repositories, with 89% of hireable users having JS repositories. Chi-square test of independence also concluded a dependancy between  hireability of user and his JS repository ownership. However, JavaScript's repository share declined by 43% in the past decade. Meanwhile, Rust, the 6th most used language, has experienced a 30-fold increase in its repository share.

- It is clear that developers should focus on enhancing their JavaScript skills, as a significant majority of hireable users possess JavaScript repositories, indicating high demand in the job market. Additionally, contributing to Rust projects could be advantageous due to its rapid growth and increasing relevance, offering new career opportunities in emerging technology sectors.

Few other interesting observations from the analysis are as below:

- Distribution of followers among users is right tailed with skewness of +5.56. This indicates that only a small number of users, possibly those with significant contributions or projects, attract a large following.
- Only 24% of users are hireable. Better job-seeking tools or networking opportunities for GitHub users can be explored.
- Companies like Spotify and Mojang have a substantial number of followers per user, suggesting that these companies foster a strong developer community.
- Correlation between no. of followers and no. of public repos is just 0.03. So, not just number of public repos, but quality of contributions may be more influential.
