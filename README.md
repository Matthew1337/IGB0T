# Web Scraping/Crawling Tutorial
A tutorial on web scraping and crawling aimed to get you up and running in 15 minutes.

 
Credentials
Make sure to update your login info in the credentials.rb file.

### 
How to Run from Command Line
To run each file navigate to the main directory (web_scraper) in your terminal and run the word
 `ruby` followed by the name of the file. Example:
`$ ruby auto_follow.rb`
or
`$ ruby auto_liker.rb`

### Updates 
- changed the ```while true``` loops to `loop do` loops with
 a break condition using a constant variable set at top
- added more variables for counting, tracking, and info output
- added
 top 100 users on instagram at the bottom of `auto_follow.rb`

### Libraries Used
[watir](https://github.com/watir/watir) for
 crawling in live browser<br>
[pry](https://github.com/pry/pry) ruby REPL<br>
[rb-readline]
(https://github.com/ConnorAtherton/rb-readline) ruby IRB and dependency of pry<br>
[awesome-print]
(https://github.com/awesome-print/awesome_print) for clearer console output
