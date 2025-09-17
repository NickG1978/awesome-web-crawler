# Awesome Web Crawlers

> Explore this curated list of most popular web crawlers to extract data from the web for many programming languages. You'll find web crawling tools for different needs. *Last update: September 2025*.

![Banner](https://github.com/ilovedevs/awesome-web-crawler/blob/main/assets/banner.jpg?raw=true)

By language:
- <img src="https://github.com/ilovedevs/awesome-web-crawler/blob/main/assets/python.svg?raw=true" width="16"/> [Python](#python)
- <img src="https://github.com/ilovedevs/awesome-web-crawler/blob/main/assets/javascript.svg?raw=true" width="16"/> [JavaScript](#javascript)
- <img src="https://github.com/ilovedevs/awesome-web-crawler/blob/main/assets/java.svg?raw=true" width="16"/> [Java](#java)
- <img src="https://github.com/ilovedevs/awesome-web-crawler/blob/main/assets/php.svg?raw=true" width="16"/> [PHP](#php)
- <img src="https://github.com/ilovedevs/awesome-web-crawler/blob/main/assets/go.svg?raw=true" width="16"/> [Golang](#golang)
- <img src="https://github.com/ilovedevs/awesome-web-crawler/blob/main/assets/c-sharp.svg?raw=true" width="16"/> [C#](#-c)
- <img src="https://github.com/ilovedevs/awesome-web-crawler/blob/main/assets/ruby.svg?raw=true" width="16"/> [Ruby](#ruby)
- <img src="https://github.com/ilovedevs/awesome-web-crawler/blob/main/assets/rust.svg?raw=true" width="16"/> [Rust](#rust)
- <img src="https://github.com/ilovedevs/awesome-web-crawler/blob/main/assets/perl.svg?raw=true" width="16"/> [Perl](#perl)
- <img src="https://github.com/ilovedevs/awesome-web-crawler/blob/main/assets/scala.svg?raw=true" width="16"/> [Scala](#scala)
- <img src="https://github.com/ilovedevs/awesome-web-crawler/blob/main/assets/r.svg?raw=true" width="16"/> [R](#r)
- <img src="https://github.com/ilovedevs/awesome-web-crawler/blob/main/assets/erlang.svg?raw=true" width="16"/> [Erlang](#erlang)
- <img src="https://github.com/ilovedevs/awesome-web-crawler/blob/main/assets/c-plus-plus.svg?raw=true" width="16"/> [C++](#c-1)
- <img src="https://github.com/ilovedevs/awesome-web-crawler/blob/main/assets/c.svg?raw=true" width="16"/> [C](#c)

## <img src="https://github.com/ilovedevs/awesome-web-crawler/blob/main/assets/star.svg?raw=true" width="23" /> Featured Web Crawlers

- [Bright Data](https://brightdata.com/) - Most popular web crawler API, especially useful to avoid blocks.
- [scrapy](https://brightdata.com/) - Fast and scalable library for Python with a huge ecosystem.
- [Puppeteer](https://github.com/puppeteer/puppeteer) - Headless Chrome automation for JavaScript, great for crawling dynamic pages.

## <img src="https://github.com/ilovedevs/awesome-web-crawler/blob/main/assets/python.svg?raw=true" width="23" /> Python

**Takeaway:** *Scrapy* remains the go-to for async and distributed crawling. *MechanicalSoup* is a good fit for simple form automation. *Newspaper3k* is suitable for news and article crawling. For lighter stacks, *you-get* handles media downloads, while *httpx* and *selectolax* give you fast building blocks for custom crawlers.

| Tool | Parsing | JS Rendering | Headless Browser | Async | Distributed |
|---|---------|--------------|----------------|--------|-------------|
| [Scrapy](https://github.com/scrapy/scrapy) | ✅ | ✅ (ext) | ✅ (ext) | ✅ | ✅ (ext) |
| [MechanicalSoup](https://github.com/hickford/MechanicalSoup) | ✅ | ❌ | ❌ | ❌ | ❌ |
| [you-get](https://github.com/soimort/you-get) | ❌ (media DL, not HTML) | ❌ | ❌ | ❌ | ❌ |
| [newspaper3k](https://github.com/codelucas/newspaper) | ✅ | ❌ | ❌ | ✅ (threaded) | ❌ |
| [httpx](https://github.com/encode/httpx) | ❌ | ❌ | ❌ | ✅ | ❌ |
| [selectolax](https://github.com/rushter/selectolax) | ✅ | ❌ | ❌ | ❌ | ❌ |


### Recommended

- [Scrapy](https://github.com/scrapy/scrapy) — Fast high-level web crawling and scraping framework.
  - [Scrapyd](https://github.com/scrapy/scrapyd) — Deploy and schedule Scrapy spiders.
  - [Scrapy-Redis](https://github.com/rmax/scrapy-redis) — Redis-backed queues.
- [MechanicalSoup](https://github.com/hickford/MechanicalSoup) — Automate HTML form navigation (Requests + BeautifulSoup; no JS).
- [you-get](https://github.com/soimort/you-get) — CLI downloader for media pages (YouTube, etc.); not a general crawler.
- [newspaper3k](https://github.com/codelucas/newspaper) — News/article extraction (title, text, images, keywords).
- [httpx](https://github.com/encode/httpx) — Async HTTP client with HTTP/2 support (modern replacement for Requests).
- [selectolax](https://github.com/rushter/selectolax) — Fast HTML parser (libxml2-backed) for crawling pipelines.

### No longer maintained

- [pyspider](https://github.com/binux/pyspider) — Powerful but now-archived web crawling and task scheduling framework with a web UI.
- [django-dynamic-scraper](https://github.com/holgerd77/django-dynamic-scraper) — Scraper framework built on Django, designed for content aggregation projects.
- [scrapy-cluster](https://github.com/istresearch/scrapy-cluster) — Distributed scraping architecture built on Scrapy, Kafka, and Redis.
- [distribute_crawler](https://github.com/gnemoug/distribute_crawler) — Simple distributed crawler built on Python, Redis, and MongoDB.
- [cola](https://github.com/chineking/cola) — General-purpose distributed crawling framework (Python 2.7 era).
- [Demiurge](https://demiurge.readthedocs.io) — Lightweight crawling library with CSS selectors, inspired by Scrapy but simpler.
- [crawley](https://pypi.org/project/Crawley/) — Early Python crawling framework; aimed to combine scraping and ORM-like data persistence.
- [RoboBrowser](https://github.com/jmcarp/robobrowser) — Library for navigating websites with BeautifulSoup + Requests, without requiring a browser.
- [PSpider](https://github.com/xianhu/PSpider) — Educational/simple Python crawler framework; demonstrates common crawling patterns.
- [aspider](https://github.com/howie6879/aspider) — Asynchronous (asyncio-based) crawler, similar to aiohttp + Scrapy mix.
- [Portia](https://github.com/scrapinghub/portia) — Visual scraping tool from Scrapinghub; lets you build spiders by pointing and clicking.
- [Scrapely](https://github.com/scrapy/scrapely) — HTML content extraction library (template-based).
- [CoCrawler](https://github.com/cocrawler/cocrawler) — Concurrent crawling engine (check org repos for active tools).
- [brownant](https://github.com/douban/brownant) — Lightweight framework for web data extraction.
- [MSpider](https://github.com/manning23/MSpider) — Simple gevent-based spider with JS render support.
- [sukhoi](https://github.com/iogf/sukhoi) — Minimalist and fast web crawler.
- [spidy](https://github.com/rivermont/spidy) — Simple command-line crawler for quick site walks.
- [Ruia](https://github.com/howie6879/ruia) — Async scraping framework (middlewares, pipelines, asyncio-native).


## <img src="https://github.com/ilovedevs/awesome-web-crawler/blob/main/assets/javascript.svg?raw=true" width="23" /> JavaScript

**Takeaway:** *Puppeteer* and *Playwright* are the most common options when you need full JS rendering and browser automation. *Cheerio* is great for fast static HTML parsing. *Axios* or *node-fetch* provide solid async HTTP backbones for building lightweight crawlers.

| Tool | Parsing | JS Rendering | Headless Browser | Async | Distributed |
|---|---------|--------------|----------------|--------|-------------|
| [Puppeteer](https://github.com/puppeteer/puppeteer) | ✅ | ✅ | ✅ | ✅ | ❌ |
| [Playwright](https://github.com/microsoft/playwright) | ✅ | ✅ | ✅ | ✅ | ❌ |
| [Cheerio](https://github.com/cheeriojs/cheerio) | ✅ | ❌ | ❌ | ✅ | ❌ |
| [Axios](https://github.com/axios/axios) | ❌ | ❌ | ❌ | ✅ | ❌ |
| [node-fetch](https://github.com/node-fetch/node-fetch) | ❌ | ❌ | ❌ | ✅ | ❌ |
| [node-crawler](https://github.com/bda-research/node-crawler) | ✅ | ❌ | ❌ | ✅ | ❌ |

### Recommended

- [Puppeteer](https://github.com/puppeteer/puppeteer) — Official Chrome/Chromium headless browser automation library.  
- [Playwright](https://github.com/microsoft/playwright) — Cross-browser automation (Chromium, Firefox, WebKit).  
- [Cheerio](https://github.com/cheeriojs/cheerio) — Fast jQuery-like parser for static HTML.  
- [Axios](https://github.com/axios/axios) — Popular HTTP client (Promise-based).  
- [node-fetch](https://github.com/node-fetch/node-fetch) — Lightweight Fetch API implementation for Node.js.
- [node-crawler](https://github.com/bda-research/node-crawler) — Early async crawler framework (callback-based).

### No longer maintained

- [Simplecrawler](https://github.com/simplecrawler/simplecrawler) — Once-popular general purpose crawler, now inactive.  
- [x-ray](https://github.com/matthewmueller/x-ray) — Elegant scraping API built on Cheerio, now inactive.  

## <img src="https://github.com/ilovedevs/awesome-web-crawler/blob/main/assets/java.svg?raw=true" width="23" /> Java

**Takeaway:** *Apache Nutch* remains the go-to for large-scale, distributed crawling. *StormCrawler* is powerful for real-time, streaming-based crawling. *WebMagic* provides a flexible, developer-friendly framework. For lighter setups, *Crawler4j* is a classic choice for simple async crawling.  

| Tool | Parsing | JS Rendering | Headless Browser | Async | Distributed |
|---|---------|--------------|----------------|--------|-------------|
| [Apache Nutch](https://github.com/apache/nutch) | ✅ | ❌ | ❌ | ✅ | ✅ |
| [StormCrawler](https://github.com/DigitalPebble/storm-crawler) | ✅ | ❌ | ❌ | ✅ | ✅ |
| [WebMagic](https://github.com/code4craft/webmagic) | ✅ | ❌ | ❌ | ✅ | ❌ |
| [Crawler4j](https://github.com/yasserg/crawler4j) | ✅ | ❌ | ❌ | ✅ | ❌ |
| [Heritrix](https://github.com/internetarchive/heritrix3) | ✅ | ❌ | ❌ | ✅ | ✅ |

### Recommended

- [Apache Nutch](https://github.com/apache/nutch) — Large-scale, distributed crawler built on Hadoop.  
- [StormCrawler](https://github.com/DigitalPebble/storm-crawler) — Real-time, distributed web crawler built on Apache Storm.  
- [WebMagic](https://github.com/code4craft/webmagic) — Flexible, modular web scraping framework for Java.  
- [Crawler4j](https://github.com/yasserg/crawler4j) — Simple, popular open-source crawler for Java.  
- [Heritrix](https://github.com/internetarchive/heritrix3) — Internet Archive’s archival-quality web crawler.  

## <img src="https://github.com/ilovedevs/awesome-web-crawler/blob/main/assets/php.svg?raw=true" width="23" /> PHP

**Takeaway:** PHP crawling is less common than in Python or Java, but there are still solid open-source options. *Goutte* is widely used for HTML scraping with a jQuery-like API. *PHP-Crawler* and *CrawlerDetect* offer simple crawling and detection utilities. *spatie/crawler* is a modern, maintained package that integrates well with Laravel.  

| Tool | Parsing | JS Rendering | Headless Browser | Async | Distributed |
|---|---------|--------------|----------------|--------|-------------|
| [Goutte](https://github.com/FriendsOfPHP/Goutte) | ✅ | ❌ | ❌ | ❌ | ❌ |
| [spatie/crawler](https://github.com/spatie/crawler) | ✅ | ❌ | ❌ | ❌ | ❌ |
| [PHP-Crawler](https://github.com/mvdbos/php-spider) | ✅ | ❌ | ❌ | ❌ | ❌ |
| [CrawlerDetect](https://github.com/JayBizzle/Crawler-Detect) | ❌ (bot detection only) | ❌ | ❌ | ❌ | ❌ |

### Recommended

- [Goutte](https://github.com/FriendsOfPHP/Goutte) — Popular PHP web scraping library (uses Symfony DomCrawler + Guzzle).  
- [spatie/crawler](https://github.com/spatie/crawler) — Modern, Laravel-friendly web crawler built on Guzzle and Symfony components.  
- [PHP-Crawler](https://github.com/mvdbos/php-spider) — General-purpose PHP spider/crawler.  

## <img src="https://github.com/ilovedevs/awesome-web-crawler/blob/main/assets/go.svg?raw=true" width="23" /> Golang

**Takeaway:** Go’s concurrency model makes it a strong fit for building crawlers. *Colly* is the most popular framework, offering a clean API with async support. *gocrawl* and *crawley* provide flexible crawling foundations. *headless-chrome* bindings allow you to integrate JS rendering when needed.  

| Tool | Parsing | JS Rendering | Headless Browser | Async | Distributed |
|---|---------|--------------|----------------|--------|-------------|
| [Colly](https://github.com/gocolly/colly) | ✅ | ❌ | ❌ | ✅ (goroutines) | ❌ |
| [gocrawl](https://github.com/PuerkitoBio/gocrawl) | ✅ | ❌ | ❌ | ✅ | ❌ |
| [crawley](https://github.com/antchfx/crawley) | ✅ | ❌ | ❌ | ✅ | ❌ |
| [headless-chrome](https://github.com/chromedp/chromedp) | ✅ | ✅ | ✅ | ✅ | ❌ |
| [ferret](https://github.com/MontFerret/ferret) | ✅ | ✅ | ✅ | ✅ | ❌ |

### Recommended

- [Colly](https://github.com/gocolly/colly) — Popular and actively maintained Go crawling framework with simple API.  
- [gocrawl](https://github.com/PuerkitoBio/gocrawl) — Polite, extensible crawler built in Go.  
- [crawley](https://github.com/antchfx/crawley) — Go library for building simple crawlers and scrapers.  
- [chromedp](https://github.com/chromedp/chromedp) — Headless Chrome/Chromium control for Go; enables JS rendering.  
- [ferret](https://github.com/MontFerret/ferret) — Declarative web scraping language/runtime in Go, with headless browser support.  

## <img src="https://github.com/ilovedevs/awesome-web-crawler/blob/main/assets/c-sharp.svg?raw=true" width="23" /> C#

**Takeaway:** *Abot2* is the most popular and actively maintained. *DotnetSpider* is a flexible option with async/distributed support. *AngleSharp* is widely used for parsing (often combined with HTTP clients). Selenium or Playwright bindings cover headless browser automation.  

| Tool | Parsing | JS Rendering | Headless Browser | Async | Distributed |
|---|---------|--------------|----------------|--------|-------------|
| [Abot2](https://github.com/sjdirect/abot) | ✅ | ❌ | ❌ | ✅ | ❌ |
| [DotnetSpider](https://github.com/dotnetcore/DotnetSpider) | ✅ | ❌ | ❌ | ✅ | ✅ |
| [AngleSharp](https://github.com/AngleSharp/AngleSharp) | ✅ | ❌ | ❌ | ✅ | ❌ |
| [Playwright for .NET](https://github.com/microsoft/playwright-dotnet) | ✅ | ✅ | ✅ | ✅ | ❌ |
| [Selenium WebDriver](https://github.com/SeleniumHQ/selenium) | ✅ | ✅ | ✅ | ✅ | ❌ |

### Recommended

- [Abot2](https://github.com/sjdirect/abot) — Lightweight, extensible web crawler for .NET Core/Framework.  
- [DotnetSpider](https://github.com/dotnetcore/DotnetSpider) — High-level crawling framework with async/distributed features.  
- [AngleSharp](https://github.com/AngleSharp/AngleSharp) — HTML5 parser and CSS selector engine for .NET.  
- [Playwright for .NET](https://github.com/microsoft/playwright-dotnet) — Browser automation for Chromium, Firefox, and WebKit.  
- [Selenium WebDriver](https://github.com/SeleniumHQ/selenium) — Cross-language browser automation; mature and widely used.  

## <img src="https://github.com/ilovedevs/awesome-web-crawler/blob/main/assets/ruby.svg?raw=true" width="23" /> Ruby

**Takeaway:** Ruby’s ecosystem leans heavily on Nokogiri for parsing, but there are a few solid crawling libraries. *Anemone* and *Spidr* are the classic general-purpose crawlers. *Mechanize* is popular for automating form submissions and link following. For JS-heavy sites, Ruby relies on Selenium or Playwright bindings.  

| Tool | Parsing | JS Rendering | Headless Browser | Async | Distributed |
|---|---------|--------------|----------------|--------|-------------|
| [Anemone](https://github.com/chriskite/anemone) | ✅ | ❌ | ❌ | ❌ | ❌ |
| [Spidr](https://github.com/postmodern/spidr) | ✅ | ❌ | ❌ | ❌ | ❌ |
| [Mechanize](https://github.com/sparklemotion/mechanize) | ✅ | ❌ | ❌ | ❌ | ❌ |
| [Ferrum](https://github.com/rubycdp/ferrum) | ✅ | ✅ | ✅ | ✅ | ❌ |
| [Capybara](https://github.com/teamcapybara/capybara) | ✅ | ✅ | ✅ | ✅ | ❌ |
| [Watir](https://github.com/watir/watir) | ✅ | ✅ | ✅ | ✅ | ❌ |

### Recommended

- [Anemone](https://github.com/chriskite/anemone) — Simple, extensible web crawler for Ruby.  
- [Spidr](https://github.com/postmodern/spidr) — Flexible Ruby library for spidering websites.  
- [Mechanize](https://github.com/sparklemotion/mechanize) — Automates website interaction (forms, links, sessions).  
- [Ferrum](https://github.com/rubycdp/ferrum) — Headless Chrome driver for Ruby.  
- [Capybara](https://github.com/teamcapybara/capybara) — Acceptance test framework with crawling/automation capabilities.  
- [Watir](https://github.com/watir/watir) — Ruby browser automation library built on Selenium/WebDriver.  

## <img src="https://github.com/ilovedevs/awesome-web-crawler/blob/main/assets/rust.svg?raw=true" width="23" /> Rust

**Takeaway:** *reqwest* and *surf* provide async HTTP backbones, while *select.rs* and *scraper* handle parsing. *fantoccini* and *thirtyfour* enable browser automation for JS-heavy sites. Dedicated crawling frameworks like *crawly* are emerging, but most work is still done with building blocks.  

| Tool | Parsing | JS Rendering | Headless Browser | Async | Distributed |
|---|---------|--------------|----------------|--------|-------------|
| [reqwest](https://github.com/seanmonstar/reqwest) | ❌ | ❌ | ❌ | ✅ | ❌ |
| [surf](https://github.com/http-rs/surf) | ❌ | ❌ | ❌ | ✅ | ❌ |
| [scraper](https://github.com/causal-agent/scraper) | ✅ | ❌ | ❌ | ❌ | ❌ |
| [select.rs](https://github.com/utkarshkukreti/select.rs) | ✅ | ❌ | ❌ | ❌ | ❌ |
| [fantoccini](https://github.com/jonhoo/fantoccini) | ✅ | ✅ | ✅ | ✅ | ❌ |
| [thirtyfour](https://github.com/stevepryde/thirtyfour) | ✅ | ✅ | ✅ | ✅ | ❌ |
| [crawly](https://github.com/jaemk/crawly) | ✅ | ❌ | ❌ | ✅ | ❌ |

### Recommended

- [reqwest](https://github.com/seanmonstar/reqwest) — Popular async HTTP client, great for building custom crawlers.  
- [scraper](https://github.com/causal-agent/scraper) — CSS selector-based HTML parser for Rust.  
- [fantoccini](https://github.com/jonhoo/fantoccini) — High-level WebDriver client for controlling browsers.  
- [thirtyfour](https://github.com/stevepryde/thirtyfour) — Selenium/WebDriver automation library for Rust.  
- [crawly](https://github.com/jaemk/crawly) — Early Rust crawling framework built on async foundations.  

## <img src="https://github.com/ilovedevs/awesome-web-crawler/blob/main/assets/perl.svg?raw=true" width="23" /> Perl

**Takeaway:** Perl’s crawling ecosystem is older but still functional. *WWW::Mechanize* is the classic choice for automating browsing and scraping. *Mojo::UserAgent* (part of Mojolicious) provides async HTTP requests and is often used as a crawler base. *Web::Scraper* offers CSS selector-style scraping. For JS-heavy sites, Perl relies on Selenium bindings.  

| Tool | Parsing | JS Rendering | Headless Browser | Async | Distributed |
|---|---------|--------------|----------------|--------|-------------|
| [WWW::Mechanize](https://metacpan.org/pod/WWW::Mechanize) | ✅ | ❌ | ❌ | ❌ | ❌ |
| [Mojo::UserAgent](https://metacpan.org/pod/Mojo::UserAgent) | ❌ | ❌ | ❌ | ✅ | ❌ |
| [Web::Scraper](https://metacpan.org/pod/Web::Scraper) | ✅ | ❌ | ❌ | ❌ | ❌ |
| [Selenium::Remote::Driver](https://metacpan.org/pod/Selenium::Remote::Driver) | ✅ | ✅ | ✅ | ✅ | ❌ |

### Recommended

- [WWW::Mechanize](https://metacpan.org/pod/WWW::Mechanize) — Classic Perl module for automating web interactions and scraping.  
- [Mojo::UserAgent](https://metacpan.org/pod/Mojo::UserAgent) — Async HTTP client in Mojolicious, useful as a crawler foundation.  
- [Web::Scraper](https://metacpan.org/pod/Web::Scraper) — Simple CSS selector-based scraping library for Perl.  
- [Selenium::Remote::Driver](https://metacpan.org/pod/Selenium::Remote::Driver) — Selenium WebDriver bindings for Perl, enables browser automation.

## <img src="https://github.com/ilovedevs/awesome-web-crawler/blob/main/assets/scala.svg?raw=true" width="23" /> Scala

**Takeaway:** *WebSpider* and *scala-crawler* exist as lightweight libraries, while *Sparkling* and *Scalding* are used when integrating crawling with big data processing. For heavy-duty crawling, Scala projects often rely directly on Java tools like Nutch or StormCrawler.  

| Tool | Parsing | JS Rendering | Headless Browser | Async | Distributed |
|---|---------|--------------|----------------|--------|-------------|
| [scala-crawler](https://github.com/ruippeixotog/scala-crawler) | ✅ | ❌ | ❌ | ✅ (Akka) | ❌ |
| [web-spider](https://github.com/gaocegege/web-spider) | ✅ | ❌ | ❌ | ✅ | ❌ |
| [crawler4j (via Java interop)](https://github.com/yasserg/crawler4j) | ✅ | ❌ | ❌ | ✅ | ❌ |
| [StormCrawler (via Java interop)](https://github.com/DigitalPebble/storm-crawler) | ✅ | ❌ | ❌ | ✅ | ✅ |
| [Apache Nutch (via Java interop)](https://github.com/apache/nutch) | ✅ | ❌ | ❌ | ✅ | ✅ |

### Recommended

- [scala-crawler](https://github.com/ruippeixotog/scala-crawler) — Scala DSL for writing crawlers on top of Akka actors.  
- [web-spider](https://github.com/gaocegege/web-spider) — Simple crawler written in Scala.  
- [crawler4j](https://github.com/yasserg/crawler4j) — Popular Java crawler, usable in Scala via JVM interop.  
- [StormCrawler](https://github.com/DigitalPebble/storm-crawler) — Real-time distributed crawler on Apache Storm (Scala-friendly).  
- [Apache Nutch](https://github.com/apache/nutch) — Large-scale distributed crawler on Hadoop (usable from Scala). 
- [scala-scraper](https://github.com/ruippeixotog/scala-scraper) — Great for HTML scraping, but not a full crawler.  

## <img src="https://github.com/ilovedevs/awesome-web-crawler/blob/main/assets/r.svg?raw=true" width="23" /> R

**Takeaway:** R is not commonly used for large-scale crawling, but it has several packages for scraping and lightweight crawling. *rvest* is the most popular for HTML scraping, while *Rcrawler* provides a more complete crawling framework. For HTTP requests, *httr2* and *curl* are the go-to packages. For JS-heavy sites, R typically delegates to Selenium or RSelenium.  

| Tool | Parsing | JS Rendering | Headless Browser | Async | Distributed |
|---|---------|--------------|----------------|--------|-------------|
| [Rcrawler](https://github.com/salimk/Rcrawler) | ✅ | ❌ | ❌ | ❌ | ❌ |
| [rvest](https://github.com/tidyverse/rvest) | ✅ | ❌ | ❌ | ❌ | ❌ |
| [httr2](https://github.com/r-lib/httr2) | ❌ | ❌ | ❌ | ❌ | ❌ |
| [curl](https://github.com/jeroen/curl) | ❌ | ❌ | ❌ | ✅ | ❌ |
| [RSelenium](https://github.com/ropensci/RSelenium) | ✅ | ✅ | ✅ (via Selenium) | ❌ | ❌ |

### Recommended

- [Rcrawler](https://github.com/salimk/Rcrawler) — Web crawler and scraper for R, supports data collection and storage.  
- [rvest](https://github.com/tidyverse/rvest) — Tidyverse package for scraping HTML using CSS selectors/XPath.  
- [httr2](https://github.com/r-lib/httr2) — Modern HTTP client for R, useful for building custom crawlers.  
- [RSelenium](https://github.com/ropensci/RSelenium) — R bindings to Selenium WebDriver for browser automation.  

## <img src="https://github.com/ilovedevs/awesome-web-crawler/blob/main/assets/erlang.svg?raw=true" width="23" /> Erlang

**Takeaway:** *Crawly* is the most notable, offering a Scrapy-like framework in Erlang. Other efforts are experimental or niche. For JS rendering or browser automation, Erlang typically defers to external tools through ports or Elixir bindings.  

| Tool | Parsing | JS Rendering | Headless Browser | Async | Distributed |
|---|---------|--------------|----------------|--------|-------------|
| [Crawly](https://github.com/oltarasenko/crawly) | ✅ | ❌ | ❌ | ✅ | ✅ |
| [Spider](https://github.com/erlware/spider) | ✅ | ❌ | ❌ | ✅ | ❌ |
| [Hackney](https://github.com/benoitc/hackney) | ❌ | ❌ | ❌ | ✅ | ❌ |

### Recommended

- [Crawly](https://github.com/oltarasenko/crawly) — Erlang crawling framework inspired by Scrapy; supports async and distributed crawling.  
- [Spider](https://github.com/erlware/spider) — Early Erlang crawler for simple spidering tasks.  
- [Hackney](https://github.com/benoitc/hackney) — HTTP client for Erlang, often used as a foundation for crawlers.  

## <img src="https://github.com/ilovedevs/awesome-web-crawler/blob/main/assets/c-plus-plus.svg?raw=true" width="23" /> C++

**Takeaway:** C++ isn’t a mainstream language for high-level web crawling, but its performance makes it useful in low-level or custom crawling systems. Libraries like *Heritrix* are Java-based, so in C++ you mostly find lighter frameworks, HTML parsers, or bindings to browser engines. Some older projects exist, but many are inactive.  

| Tool | Parsing | JS Rendering | Headless Browser | Async | Distributed |
|---|---------|--------------|----------------|--------|-------------|
| [StormCrawler++](https://github.com/comtravo/stormcrawler-cpp) | ✅ | ❌ | ❌ | ✅ | ✅ |
| [C++ Requests (cpr)](https://github.com/libcpr/cpr) | ❌ | ❌ | ❌ | ✅ | ❌ |
| [QtWebKit / QtWebEngine](https://doc.qt.io/qt-6/qtwebengine-overview.html) | ✅ | ✅ | ✅ | ✅ | ❌ |
| [Casablanca (cpprestsdk)](https://github.com/microsoft/cpprestsdk) | ❌ | ❌ | ❌ | ✅ | ❌ |

### Recommended

- [StormCrawler++](https://github.com/comtravo/stormcrawler-cpp) — C++ implementation of crawler components for distributed systems.  
- [cpr](https://github.com/libcpr/cpr) — C++ Requests: simple HTTP client, often used to build crawlers.  
- [QtWebEngine](https://doc.qt.io/qt-6/qtwebengine-overview.html) — Chromium-based engine for headless browsing in C++.  
- [cpprestsdk](https://github.com/microsoft/cpprestsdk) — Microsoft’s REST SDK for HTTP and JSON; good for building crawler backbones.  

## <img src="https://github.com/ilovedevs/awesome-web-crawler/blob/main/assets/c.svg?raw=true" width="23" /> C

**Takeaway:** Crawlers in C typically rely on libraries like *libcurl* for HTTP and *libxml2* for parsing. There are a few simple open-source crawler projects, but most large-scale crawling is delegated to higher-level languages.  

| Tool | Parsing | JS Rendering | Headless Browser | Async | Distributed |
|---|---------|--------------|----------------|--------|-------------|
| [libcurl](https://github.com/curl/curl) | ❌ | ❌ | ❌ | ✅ | ❌ |
| [libxml2](https://gitlab.gnome.org/GNOME/libxml2) | ✅ | ❌ | ❌ | ❌ | ❌ |
| [Heritrix C port (experimental)](https://github.com/internetarchive/heritrix3) | ✅ | ❌ | ❌ | ❌ | ❌ |
| [SimpleCrawler-C](https://github.com/jaysonlong/SimpleCrawler) | ✅ | ❌ | ❌ | ❌ | ❌ |

### Recommended

- [libcurl](https://github.com/curl/curl) — Core C library for HTTP(S), FTP, and other protocols, often the base for crawlers.  
- [libxml2](https://gitlab.gnome.org/GNOME/libxml2) — XML/HTML parser library, used for content extraction.  
- [SimpleCrawler-C](https://github.com/jaysonlong/SimpleCrawler) — Minimal educational web crawler in C.

## 🤖 For LLM / AI / RAG  

Focused on clean text extraction and browser automation for feeding RAG pipelines:
- [Scrapy](https://github.com/scrapy/scrapy) (Python).
- [MechanicalSoup](https://github.com/hickford/MechanicalSoup) (Python). 
- [Playwright](https://github.com/microsoft/playwright) (JavaScript).
- [chromedp](https://github.com/chromedp/chromedp) (Golang).
- [DotnetSpider](https://github.com/dotnetcore/DotnetSpider) (C#). 


## 🛒 For E-Commerce  

Optimized for product pages, price monitoring, and large catalogs:  

- [Scrapy](https://github.com/scrapy/scrapy) (Python).
- [Cheerio](https://github.com/cheeriojs/cheerio) (JavaScript / Node.js). 
- [Colly](https://github.com/gocolly/colly) (Golang).
- [Abot2](https://github.com/sjdirect/abot) (C#).
- [spatie/crawler](https://github.com/spatie/crawler) (PHP).

## ⚡ For Dynamic Content  

Handles SPAs and JS-heavy sites with headless browser automation:

- [Scrapy + Playwright](https://github.com/scrapy-plugins/scrapy-playwright) (Python).
- [Puppeteer](https://github.com/puppeteer/puppeteer) (JavaScript / Node.js).
- [chromedp](https://github.com/chromedp/chromedp) (Golang).
- [Ferrum](https://github.com/rubycdp/ferrum) (Ruby).
- [thirtyfour](https://github.com/stevepryde/thirtyfour) (Rust). 

## 🔍 SEO Crawling  

Built for audits, link checks, and technical SEO signals:  

- [Scrapy](https://github.com/scrapy/scrapy) (Python).
- [node-crawler](https://github.com/bda-research/node-crawler) (JavaScript / Node.js).
- [Goutte](https://github.com/FriendsOfPHP/Goutte) (PHP).
- [Rcrawler](https://github.com/salimk/Rcrawler) (R).
- [Crawly](https://github.com/oltarasenko/crawly) (Erlang).

## 📚 Articles  

- [Bright Data vs Oxylabs: Scraping APIs](https://medium.com/@ScrapingData/bright-data-vs-oxylabs-scraping-apis-c9235885674f) — In-depth comparison of two major crawling APIs.

