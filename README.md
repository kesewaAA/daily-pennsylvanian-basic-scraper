# Daily Pennsylvanian Scraper
This is a web scraper that scrapes the daily pennsylvanian for opinion news article headlines. 

## Overview / Modifications
I modified the original scraper such that instead of scraping "a" headlines directly from the dp.com link,
it scrapes the heading "h3" under class "standard-link" from the ".../section/opinion" link of the daily pennsylvanian.
I opted to get opinion insights as I thought this would be interesting and the headlines are usually constructed in 
an eye-catching manner

## Cron Syntax
'0 20 * * *' refers to minute 0, at 20:00 hour, '*' every day of the month,  '*' every month and  '*' every week. Thus it essentially means that the workflow will run at 8:00pm daily. 


## Licensing

This software is distributed under the terms of the MIT License. You have the freedom to use, modify, distribute, and sell it for any purpose. However, you must include the original copyright notice and the permission notice found in the LICENSE file in all copies or substantial portions of the software.


## Ethical considerations

