🌐 Miscellaneous Web Concepts — Short Notes
1) What is HTTP?

HTTP (HyperText Transfer Protocol) is the communication rule used by browsers and servers to exchange data on the web.

👉 In simple words:
When you open a website, your browser sends an HTTP request to the server, and the server sends back an HTTP response (HTML, images, etc.).

👉 Example flow:
Browser → sends request → Server
Server → sends webpage → Browser

👉 Without HTTP, websites cannot load.

--------------------------------------------------------

2) HTTP Methods (GET vs POST vs PUT)

These are ways a browser communicates with the server.

1. GET

Used to request/fetch data from the server

Data is sent in the URL

Should NOT be used for sensitive data

Can be cached and bookmarked

👉 Example: loading a webpage or search query

👉 Interview line:
GET is used to retrieve data from a server.

2. POST

Used to send data to the server

Data is sent in the request body, not URL

Used in forms (login/signup)

More secure than GET

👉 Example: submitting a login form

👉 Interview line:
POST is used to submit data to a server.

3. PUT

Used to update existing data on the server

Replaces the resource completely

Mostly used in APIs (not basic HTML forms)

👉 Example: updating a user profile in a REST API

👉 Interview line:
PUT is used to update existing data on a server.

Quick Comparison Table
Method	Purpose	Where data goes	Common Use
GET	Fetch data	URL	Load page/search
POST	Send new data	Body	Forms/login
PUT	Update data	Body	APIs/update
One-line Interview Summary

👉 HTTP is the protocol that allows browsers and servers to communicate, and methods like GET, POST, and PUT define what action we want to perform on the server.