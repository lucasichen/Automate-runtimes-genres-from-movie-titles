# Movie Database runtime and genre generator

This code uses the Google and IMDB API to read a google sheets document for movie titles and will write runtimes and genres based on those titles. This only works if you have enabled, added a credential for google sheets api to your account, and shared the sheet to your API. To set this up use Google sheets API for python: https://developers.google.com/sheets/api/quickstart/python. Then add the credentials file to your code folder named: "keys.json"

For a database to test with: https://docs.google.com/spreadsheets/d/1THzIKMPwwajUT4dxxUWwL-kjMAx3y4FJrAGQVZE68qw/edit?usp=sharing

Pictures below show example of before and after:

![Database%20before](https://github.com/lucasichen/Create-title-genre-from-movie-database/blob/main/Database%20before.png)
![Database%20after](https://github.com/lucasichen/Create-title-genre-from-movie-database/blob/main/Database%20after.png)

Feel free to add me and message me if you want to let me know a better way to write this code or a way to decrese the changes of Null cases.
