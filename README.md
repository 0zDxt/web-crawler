```
·····························································
:              _        ____                    _           :
:__      _____| |__    / ___|_ __ __ ___      _| | ___ _ __ :
:\ \ /\ / / _ \ '_ \  | |   | '__/ _` \ \ /\ / / |/ _ \ '__|:
: \ V  V /  __/ |_) | | |___| | | (_| |\ V  V /| |  __/ |   :
:  \_/\_/ \___|_.__/   \____|_|  \__,_| \_/\_/ |_|\___|_|   :
·····························································
```


# Web Crawler
A Python script to crawl websites and track internal/external links

## Description
This script uses 'requests' to fetch wab pages and 're' for links extraction. It supports a command line argument to specify the domain to crawl.

## Installation
1. Clone the repository

git clone https://github.com/MxSns/web-crawler.git

2. Install dependencies
pip3 install -r requirements.txt

## Usage
Run the script with a domain argument

python3 web_crawler.py -d <url>

## Output
Crawled URLs:
List of visited internal links
External URLs:
List on links pointing outside the domain
