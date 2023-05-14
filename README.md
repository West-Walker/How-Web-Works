# How-Web-Works


1)
Hyper-Text Transfer Protocol governs how clients get information from, and send information to, a server.
2)
Uniform Resource Locator or URL, is an address for any internet resource.
3)
Domain Name System or DNS,  is a system that takes spoken language URLs and transforms them into IP addresses.
4)
The query string allows you to pass key-value pairs into the URL.
5)
GET - get some information from the server.
POST - send some information to the server.
6)
An HTTP request is a request from a client to a server which follows the HTTP protocol.
7)
An HTTP response is a response from a server to a client which follows the HTTP protocol.
8)
Headers provide additional information about the request or the response. Examples include:
Request headers: Accept-Language, Host, Cache-Control, User-Agent, Cookie.
Response headers: Last-Modified, Content-Type, Set-Cookie, Status code..
9)
Your browser “resolves” the name into an IP address using DNS
Your browser makes a request to that IP address, including headers (info about browser, any previous cookies, and other things)
The server sends a response (typically, HTML, with a status code (200 if it was successful)
The browser makes a DOM from that HTML, and finds any other resources needed (images, CSS, JavaScript, etc)
The browser makes separate HTTP requests for those resources and receives response from the server for each
