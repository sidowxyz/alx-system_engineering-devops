# 0x16. API Advanced

## Project Overview

This project focuses on interacting with the Reddit API to practice making API calls, parsing JSON data, handling pagination, and writing recursive functions in Python. It aims to improve skills commonly required in technical interviews and for practical use in scripting and backend development.

## Tasks

### 0. How Many Subs?
- **File:** `0-subs.py`
- **Function:** `number_of_subscribers(subreddit)`
- **Description:** Queries the Reddit API to return the total number of subscribers for a given subreddit. If the subreddit is invalid, the function returns `0`.

### 1. Top Ten
- **File:** `1-top_ten.py`
- **Function:** `top_ten(subreddit)`
- **Description:** Queries the Reddit API to print the titles of the first 10 hot posts listed for a given subreddit. If the subreddit is invalid, it prints `None`.

### 2. Recurse It!
- **File:** `2-recurse.py`
- **Function:** `recurse(subreddit, hot_list=[])`
- **Description:** A recursive function that queries the Reddit API and returns a list containing the titles of all hot articles for a given subreddit. Returns `None` if the subreddit is invalid.

### 3. Count It!
- **File:** `100-count.py`
- **Function:** `count_words(subreddit, word_list)`
- **Description:** A recursive function that queries the Reddit API, parses the titles of all hot articles, and prints a sorted count of given keywords (case-insensitive). The results are sorted by the count in descending order and alphabetically for ties. If the subreddit is invalid, the function prints nothing.

## Getting Started

### Prerequisites

- Python 3.4 or later
- `requests` module (`pip install requests`)

### Running the Scripts

To execute any of the Python scripts, use the command:

```bash
python3 <script_name.py> <subreddit> [<word_list>]
```

For example, to get the number of subscribers for the subreddit "programming":

```bash
python3 0-main.py programming
```

### Note

- Ensure you use a custom User-Agent when making requests to avoid being blocked by Reddit's API rate limits.
- The scripts are designed to avoid following redirects, which could lead to invalid results.

## Author

- **GitHub:** [sidowxyz](https://github.com/sidowxyz)

