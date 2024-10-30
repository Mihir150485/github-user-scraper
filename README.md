# github-user-scraper
for study purpose
# GitHub User Scraper

- This project scrapes GitHub users based in a specified city with more than a defined number of followers, along with their repositories.
- The data is saved in two CSV files: `users.csv` for user information and `repositories.csv` for repository details.
- The script is written in Python and uses the GitHub API for data collection.

## How to Use

1. Replace `${city}` and `${followers}` in `scrape_users.py` with your desired city and minimum followers.
2. Obtain a personal access token from GitHub and replace `YOUR_GITHUB_TOKEN` in the script.
3. Run the script using Python.

```bash
python scrape_users.py
