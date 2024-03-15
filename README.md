# webcrawl
Web enumeration code for find (crawl) all urls from each page on the site. for linux only.
The idea is to run enumeration based on the link href that the landing pages contain. In that way we can build a list which contain any url that found on the site.
In case you didn't find any interesting you may want to run webenun for enumerate for hidden pages and then run the web crawling again.

# how to run
python3 ./webcrawl.py <url>

# how to install
wget https://raw.githubusercontent.com/Zwerd/webcrawl/main/webcrawl%2Cpy;
chmod +x ./webcrawl.py
