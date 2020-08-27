# Github-API
A python flask project which user beautifulsoup to scrape github and get the user repositories

# Documentation
URL= http://gitapi.pythonanywhere.com/
* /repo/id {id=github username }
  * Gives you the repository details

    ```javascript
    [{
    "description":"A python flask project which user beautifulsoup to scrape github and get the user repositories",
    "name":"Github-API",
    "stars":"1",
    "url":"https://github.com/fredysomy/Github-API"
    }]
    ```
     I will return the first 30 repos in your account.
   ```/user/id {id=github username }```<br>
     Gives some datails of user<br>
    ```javascript {"Followers": "10","Following": "26","Total_stars": "69"} ```<br>
     *_features yet to be added_*
### MORE FEATURES TO BE ADDED.

