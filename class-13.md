# The Past, Present & Future of Local Storage for Web Applications | Mark Pilgrim

## Native Client Applications vs. Web Applications

Historically, Native Client Applications were preferred to web applications due to the ability for persistent local storage. 

Cookies came along as an improvement, but due to loading time with every HTTP request they would:  
- slow down web application loading time
- send data unencrypted over the internet
- additionally, Cookies are limited to ~4KB of data, which makes them less useful overall

## HTML5  

HTML5 now allows for a lot of client-hosted storage space that is not transmitted to the server and persists beyond a page refresh. 

**Storage**  
- Based on named key/value pairs.
- Data can be any time supported by JavaScript
    - stored as a string

## User Data 

userData allows web pages to store up to 64KB of data per domain.  
- uses XML-based structure


*This information was referenced from* [HERE!](http://diveinto.html5doctor.com/storage.html)  

[**Return to Home**](README.md)