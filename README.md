# you tube's data scraping using selenium
**Introduction**
this is a youtube comment scrapper which is able to scrap comments from youtube videos
you can extract comments for any footage, most web pages including youtube are dynamic they change automatically so due to this I use Selenium which is a powerful tool for it. choose and insert the name of the video wisely because it is programmed to scrap the 1st video's comment from the search list.

**requirment**
- Python 3.11.3
- selenium 4.10.0

**How to Use**
```python
#put the keyword and full name of the video want to scrap 
search.send_keys(" ")


in the  send key put the name or keyword of the video you want to scrap it will automate the work and at last it will provide a CSV file that contains all the comments. the name of the CSV file will be *you_tube_comment_1.csv*


