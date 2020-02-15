I tried to crawl company information from crunchbase and owler. The websites have some basic anti-crawling techniques. So I use chromewhip to cheat the website and crawl information successfully.



I am assigned to a data collection task, to collect 2000 company information from [owler](www.owler.com) and [crunchbase](www.crunchbase.com)

Collecting structured data by hand and feed them into an excel table is always boring and time consuming. So I tried to use web crawl method to solve it and save some time (50 hours work estimated).

I should get the following information from the two websites: Company name (in two websites), Company Business, Category	Company Revenue, Competitor count (cap at 10), Competitor Revenue in Total	HHI, top 10 competitors revenue.

The websites have some anti web crawling techniques, so we could not use the basic methods to crawl.

At first I tried some easy ways: https://github.com/mengmeng12/crawl_company_info/blob/master/company_info_crawl.ipynb
I can get some information at first, but the website has some anti robot examination which requires human verification.

Then I use chromewhip to mimic real human's interaction with website, in https://github.com/mengmeng12/crawl_company_info/blob/master/chromewhip1.ipynb

*mimic human example:*
<video width="640" height="480" controls>
<source src="https://mengmeng12.github.io/blog/webcrawl.mp4">
</video>

I also wrote some function to calculate some index and ratio and did some other anti anti-web crawl things.

The final result is here: https://github.com/mengmeng12/crawl_company_info/blob/master/data/whole_info_v4.csv

The codes really save me from a very heavy work and helps me to understand web crawl better.







