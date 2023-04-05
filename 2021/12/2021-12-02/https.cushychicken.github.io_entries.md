## Some guidelines for writing web scrapers
 - [https://cushychicken.github.io/rules-for-web-scrapers/](https://cushychicken.github.io/rules-for-web-scrapers/)
 - RSS feed: https://cushychicken.github.io
 - date published: 2021-12-02 23:30:57.512263+00:00

I’ve been working on www.rtljobs.com, a job board for RTL and FPGA engineers, since September. Right now, RTLjobs is an aggregator. We index open FPGA/RTL roles at a number of companies, check them for relevance, and post them to our site. I’ve already written two job scraping systems to help ease the work of indexing jobs. Here’s some general rules I’ve come to hold for writing web scrapers and other ETL systems.

