# USC Class Schedule Listing Scraper

This program is a little scraper for the [USC Class Schedule website](https://ssb.onecarolina.sc.edu/BANP/bwckschd.p_disp_dyn_sched).

It is written as a Python Notebook called [ParseSchedule.ipynb](http://nbviewer.ipython.org/github/USCSoftware/parseclassschedule/blob/master/ParseSchedule.ipynb) (click that to view the code).

It uses:

* BeautifulSoup
* csvkit
* requests

I used it to scrape all USC Columbia departments for Spring 2015, which came out to 9,985 section times in total.

You can grab the resulting files [schedule.csv](http://jmvidal.cse.sc.edu/schedule/schedule.csv) and [schedule.json](http://jmvidal.cse.sc.edu/schedule/schedule.json).

I have a nightly cron job that updates these files automatically.

# Contribute

I'm sure there are bugs. Let me know what you find. Even better, fix it yourself and send in a pull request.

Also, I did not grab everything I could, just everything I thought people would want. If you want me to scrape something else, let me know.
