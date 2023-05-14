# Web Hacking
## Web Application
- A web application is a program or software that runs on a web browser to perform specific tasks.
- These web applications are made with programming languages like HTML,CSS,JS,Python(Django,Flask)
- WebSites Consists 2 parts.
   - Front End / Client side /
      - Front End is the Front page/ the page which we access, the graphical part.
      - Example: HTML,CSS,JS(react)
      - A person who develop Front end is called “Front End Developer”
  - Back End / Server Side /
     - Back End is another side of a web which users don't have interaction with it, but their requests will be sent to the server and used to fetch the data from server and hands to the front page/front end/ of the websites.
     - Example: JS(node.js),Python(Django,Flask),PHP,SQL
     - A person who develop Back end is called “Back End Developer”
- A person who develop Both Front and Back end is called “Full Stack Developer”
## HTML /HyperText Markup language/
- HTML is the standard markup language for creating Web pages.
   - Markup language refers to a text-encoding system consisting of symbols inserted in a text document to control its structure, formatting, or the relationship between its parts.
- HTML consists of a series of elements
- HTML elements tell the browser how to display the content
- HTML have elements called Tags.
- Tags are special words that have < > on their beginning and ending
- HTML languages start with a HTML tag
- Those tags have opening and closing tags.  <> … </>
   - The text between opening and closing tag is called “innerText”
   - The tags inside a tag is called “innerHTML”
- But This doesn't mean all HTML tags need Closing tag.
  - Example: <img> does not have closing tag.
### A Simple HTML Document
- The html tag contains 2 elements
  - Head tag Contain elements those does not appear on the page.
- Title and meta info’s
  - Body tag is a container for all the visible contents
- headings, paragraphs, images, hyperlinks, tables, lists, etc.
- There are heading tags
  - <h1>,<h2>,<h3>..<h5>
- Paragraph <p>
- Anchor tags <a> for linking
- Image tags <img>
- Break line(new line) <br>
- Division <div>
  - Used to do container and hold some tags inside.
## Web browsers
- The purpose of a web browser (Chrome, Edge, Firefox, Safari) is to read HTML documents and display them correctly.
- A browser does not display the HTML tags, but uses them to determine how to display the document:
## web hacking
- Web hacking refers to exploitation of applications via HTTP which can be done by manipulating the application via its graphical web interface.
- Always Hacking Steps are same on all type of attacks.
  - Information gathering
  - Scanning
  - Exploiting
## How do websites work?
- When you access a website or click a link, it will send a HTTP request to the server and get the copy of the website files to the client this is called Response.
## URL and URI
- URI identifies a resource and differentiates it from others by using a name, location, or both.
- URL identifies the web address or location of a unique resource.
- URI contains components like a scheme, authority, path, and query.
- URL has similar components to a URI, but its authority consists of a domain name and port.
- A URI aims to identify a resource and differentiate it from other resources by using the name of the resource or location of the resource.
- A URL aims to find the location or address of a resource on the web.
  - An example of a URI can be ISBN 0-486-35557-4.
  - An example of an URL is https://www.javatpoint.com
## Parts of URL
### A URL consists of five parts:
1. Scheme: tells web servers which protocol to use when it accesses a page on your website.
2. Subdomain:
a. If your website is like a house, your subdomains are like specific rooms in that house.
b. A subdomain in a URL indicates which particular page of your website the web browser should
serve up.
c. For instance, subdomains like “blog” or “offers” will provide your website’s blog page or offers
page.
d. Subdomains also bucket your website into its main content categories and shows Google and your
visitors that there's more information on your site than just a homepage.
3. Top-level domain: specifies what type of entity your organization registers as on the internet.
a. Generic Top level domain(gTLD): .gov .org .net
b. Country code Top-level domain(ccTLD): .et .ru
4. Second-level domain: is the name of your website.
5. Subdirectory: also known as a subfolder,helps people understand which particular section of a webpage they’re on.
## HTTP request and response
- As the name suggests HTTP requests are a request which the browser sends to the server
- HTTP responses are a response from the server to the browser.
- The requests and Response are sent and received with a Header.
## HTTP Headers
- The HTTP headers are used to pass information between the clients and the server through the request and response header.
- All the headers are case-insensitive, headers fields are separated by colon, key-value pairs in clear-text string format.
- The end of the header section denoted by an empty field header(New line).
### Types of Headers
1. General Header: This type of headers applied on Request and Response headers both but without affecting the database body.
2. Request Header: This type of headers contains information about the fetched request by the client.
2. Response Header: This type of headers contains the location of the source that has been requested by the client.
4. Entity Header: This type of headers contains the information about the body of the resources like Content-length.
## HTTP request methods
- The method designates the type of request being made to the web server.
- The most common types of request methods are GET and POST but there are many others, including HEAD, PUT, DELETE, CONNECT, and OPTIONS.
- GET and POST are widely supported while support for other methods is sometimes limited but expanding.
## HTTP Status Code
- The Status-Code element in a server response
- is a 3-digit integer where the first digit of the Status-Code defines the class of response and the last two digits do not have any categorization role.
- There are 5 values for the first digit:
  - 1xx: Informational  means the request has been received and the process is continuing.
  - 2xx: Success  means the action was successfully received, understood, and accepted.
      - for example 200 = request is Successful(OK)
  - 3xx: Redirection  means further action must be taken in order to complete the request.
      - for example  301 = The requested page has moved to a new url . (Moved Permanently)
  - 4xx: Client Error  means the request contains incorrect syntax or cannot be fulfilled.
      - for example 404 = The server can not find the requested page.(Not Found)
  - 5xx: Server Error  means the server failed to fulfill an apparently valid request.
      - for example 500 = The request was not completed. The server met an unexpected condition.(Internal Server Error)
## Where do you see the headers?
- The headers are shown on some methods.
1. Developers tool(on browser)
2. Curl
3. Burp suite
- Developers tool
- To open it on browser Press Ctrl+shift+C
- This tools contains lot of things
1. Inspector:to see and edit the HTML and CSS temporarly
2. Console: to run some Javascript codes
3. Debugger: used to do debug in runtime
4. Network: to see the requests and responses
5. Storage: to store catch and cookies
- To get the requests we go to the Network tab
## Curl on linux
- cURL, which stands for client URL, is a command line tool that developers use to transfer data to and from a server.
- At the most fundamental, cURL lets you talk to a server by specifying the location (in the form of a URL) and the data you want to send.
- cURL supports several different protocols, including HTTP and HTTPS, and runs on almost every platform.
- This makes cURL ideal for testing communication from almost any device (as long as it has a command line and network connectivity) from a local server to most edge devices.
- Syntax: curl [options] [URL]
## Burp suite
- Burp or Burp Suite is a set of tools used for penetration testing of web applications.
- It is developed by the company named Portswigger, which is also the alias of its founder Dafydd Stuttard.
- BurpSuite aims to be an all in one set of tools and its capabilities can be enhanced by installing add-ons that are called BApps.
- Burp Suite is an integrated platform and graphical tool for performing security testing of web applications
- it supports the entire testing process, from initial mapping and analysis of an application's attack surface, through to finding and exploiting security vulnerabilities.
- It have a lot of tools all together.
- Simply Help Hackers To Act like A Proxy, it will intercept A request, Used to change it or just watch it
### Installing
- Burpsuite have 2 versions
  - Community = free
  - Enterprise - paid
  - Professional - paid
## OWASP Top 10
- OWASP Stands fro Open Web Application Security Project.
- The OWASP Top 10 is a standard awareness document for developers and web application security.
- It represents about the most critical security risks to web applications.
- Globally recognized by developers as the first step towards more secure coding.
- This Project Realeases Top 10 risky vulns every 4 years.
- OWASP also releases API vulnerabilities
## BruteForce
- It is included in Broken Authentication/Access Control Bug
- This is a kind of attack that is usually done to a login pages.
- It uses Wordlist and try to check a lot of words in the place of the username and password.
- It is a guessing game but the guess is done with computer.
## XSS
- It is included in Injection Bug
- XSS/ Cross site scripting/ is a vulnerability that leads to a lot of huge attacks.
- This Bug is exploited. As the following
  - If there is a search place and teh search place expects a text to search and displays below.
  - But if we add some html/JS codes on that place, this means it will add the code to the innerHTML
  - SO our code will be executed!
## SQL injection
- It is included in Injection Bug
- It is same with xss, but here we will add a sql code to the search place.
- SQL is a query language used in Back end to retrive data from database.
- Most of the time used to byoass login pages.
## Rate limit
- This is a limiting problem.
- Think like if the developers did made a limit to some task.
## Access Control
- This is a problem occurd on how a websites control an access of a user.
- Then think that normal user can get access of admins or root user.
## IDOR
- IDOR/ Insecure direct object references /: is a bug included in Access Control.
- This is a bug that happenes when you have an id number 1
- And is abebe is id 1 then if i changed that number to 0 and got another users information Bussiness Logic
- This Bug is a logic Flow.
- It occurs by the way how the programmer thinks and hackers thinking.
- Think like if You have bank website and it have a purpose of send money.
- Then if i can change add to negative numbers
- And if the site responde by giveing me more money and minimizing the amount of the user i planed to send then this is bussiness logic
- Also this is a Good Bug to learn.