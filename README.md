# mongeese
Allow users to leave comments on articles scraped from a website.

Click on an article and leave a note by using the form on the right. 
Beneath this will be displayed other collected notes. You are NOT
ALLOWED to delete notes. It is forbidden.

This app uses:



It scrapes {news source} for articles and saves them in the mongo database
after checking to prevent duplicate entries. The user is provided means to attach
notes to the articles. It does not clear its database on initialization.
