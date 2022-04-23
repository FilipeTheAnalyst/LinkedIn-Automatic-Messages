# LinkedIn Automatic Connection Messages
```
A Jupyter Notebook that:
    1) LinkedIn.ipynb - Search People that worked at a company and send a connection request with a personalized message.
```
# ✨ Background

I was looking for a way that I can use automation in order to reach out to profiles of people that previously worked in a specific company I'm looking for and send a connection request with a personalized message.

# 🛑 Disclaimer

NOTICE: The use of robots or other automated means to access LinkedIn without the express permission of LinkedIn is STRICTLY PROHIBITED.  
[More details here](https://www.linkedin.com/robots.txt)

IMPORTANT NOTE: LinkedIn will BLOCK you from searching if you are scraping too much data and/or you don't have permission. 

### To begin

Prerequisites: Python installed and environment established with packages selenium, time and keyring installed.

1) [Download your appropriate chromedriver](https://chromedriver.chromium.org/downloads) and save it to this repository.
2) Create a new generic credential on Windows Credential Manager named "linkedin" with your account info (email, password)
3) Adjust the variable url_search to the company you're looking for. (in my code I'm using Farfetch)
