# What is the difference between webpage, website, web server, and search engine?

## Primary definitions 
### Web Page 
A document which can be displayed in a web browser such as Firefox, Google Chrome, Opera, Microsoft Internet Explorer or Edge, or Apple's Safari. These are also often called just "pages."

### Website 
A collection of web pages which are grouped together and usually connected together in various ways. Often called a "web site" or a "site."

### Web Server
A computer that hosts a website on the Internet.

### Search Engine 
A web service that helps you find other web pages, such as Google, Bing, Yahoo, or DuckDuckGo. Search engines are normally accessed through a web browser (e.g. you can perform search engine searches directly in the address bar of Firefox, Chrome, etc.) or through a web page (e.g. bing.com or duckduckgo.com).

## Static and Dynamic Web Servers 
A **static web server**, or stack, consists of a computer (hardware) with an HTTP server (software). We call it "static" because the server sends its hosted files as-is to your browser.

A **dynamic web server** consists of a static web server plus extra software, most commonly an application server and a database. We call it "dynamic" because the application server updates the hosted files before sending content to your browser via the HTTP server.

>For example, to produce the final webpages you see in the browser, the application server might fill an HTML template with content from a database. Sites like MDN or Wikipedia have thousands of webpages. Typically, these kinds of sites are composed of only a few HTML templates and a giant database, rather than thousands of static HTML documents. This setup makes it easier to maintain and deliver the content.

## Static vs. dynamic content

Roughly speaking, a server can serve either static or dynamic content. Remember that the term static means "served as-is". Static websites are the easiest to set up, so we suggest you make your first site a static site.

The term dynamic means that the server processes the content or even generates it on the fly from a database. This approach provides more flexibility, but the technical stack is more complex, making it dramatically more challenging to build a website.

There are so many application server technologies that it's difficult to suggest a particular one. Some application servers cater to specific website categories like blogs, wikis, or eCommerce; others are more generic. If you're building a dynamic website, take the time to choose technology that fits your needs. Unless you want to learn web server programming (which is an exciting area in itself!), you don't need to create your own application server. That's just reinventing the wheel.