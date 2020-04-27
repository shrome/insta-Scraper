## Instagram Scrapper

- Written in python
- It scraps the followers or following of a **non-private** instagram user
- Other functions as well for example -> Execute like on photo, follow user, commenting and find connection.
- Mostly utilised Selenium module for a webdriver provider
- Need to provide 3 pieces of information -> your valid instagram account **username** and **password**, your target's **username**
- Able to extract a user's ID, user_handle, is_private boolean value, is_verified boolean value, profile pic url and Full Name.
- To swap the mode between extracting followers & following, change the mode in the function defined below
```js
scrapeFollowersFromAnAccount(mode="followers") 
scrapeFollowersFromAnAccount(mode="following")

// Every executional lines is placed under 
if __name__ == "__main__":
```
- Two main python executional files -> script.py (executional) and API.py (contains all def functions)
