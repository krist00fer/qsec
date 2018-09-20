# Mission 008 - The Web Crawler Framework

## Mission Statement

Provide a re-usable open source version of a Queue Framework, meant to be used as a "code library" referenced from other projects.

## Requirements

### Generic requirements

* Library should be easy to use, compile and contribute to
* Easy to reference and use from other projects
* Library should conform to Design Guidelines, Conventions, Idioms, and Patterns normally used in the eco system

### Version 1.0 - The Basics

Provide a basic re-usable "code library" that provides the following capabilities:

Create a WebCrawler object that has the ability to:

* Retrieve the content represented by a URL
* Identify all URLs within a WebSite

### Version 1.1 - The Basics, Update 1

Introduce additional features:

* CrawlWeb - Given a URL returns all content within that URL and the referred to URLs up to N levels.

### Version 2.0 - Complexity

Introduce additional features:

* If not already implemented make sure Web Crawling is done in parallel if possible

### Version 2.1 - Complexity, Update 1

Introduce additional abilities:

* Persist visited URLs so a crawl operation can be canceled and resumed

### Version 3.0 - Scale Out

Enable the ability to run WebCrawling on several machines, all helping with the same job.
