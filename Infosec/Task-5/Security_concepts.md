# Security Concepts

## Client-Side vs Server-Side Security
### Client-Side Security
• Client-Side code is fully exposed and runs on the users' browser in the front end.
<br>
• This makes it vulnerable and easy to bypass as attackers can access code easily and manipulate it.
<br>
• Risks:
1) Cross-site Scripting
2) Reverse Engineering
3) Cross-Site Request Forgery (CSRF)
4) Magecart

<br>
• Security measures:

1) Code obsfurcation
2) Content Security Policy (CSP)
3) Input Validation and Sanitation

### Server-Side Security
• Server-side components are hidden and are executed in controlled environments.
<br>
• It is essential to secure them as they contain sensitive infomation like user data, business logic and APIs.
<br>
• Risks:
 1) SQL injection
 2) SSTIs 
 3) Distributed Denial of Service (DDoS)

 <br>
• Security measures:
<br>

1) Authentication & Authorisation
2) Encryption of data at rest and in transit
3) Web Application Firewalls (WAFs)

## HTTP Methods & Headers
### HTTP Methods
• HTTP request methods specify certain actions to be performed on resources.
<br>
• These requests are sent by clients to servers.
<br>
• Some of the common request methods include:
1) GET - Retrieves data from the server.
2) HEAD - Fetches header information without body.
3) POST - Creates new resources in the server.
4) PUT - Replaces entire data in an existing resource with the updated version.
5) PATCH - Updates specific properties of an existing resource without overwriting.
6) DELETE - Remove data from the database.

### HTTP Headers
• HTTP Headers are key-value pairs that contain metadata about the connection.
<br>
• There are 4 common HTTP Headers:
1) Client Request Header - Contains information about the request from the clients and what do they expect in return.
2) Server Response Header - Provides metadata about the response
3) General Header - Applicable to both requests and responses, and is unrelated to content.
4) Entity Header - Describe the body of the message.

## Server-Side Template Injection (SSTI)
• Server-Side Template Injection is a vulnerability that occurs when user input is directly embedded into the template engine.
<br>
• SSTI attacks web servers' internals and obtain RCE (Remote Code Execution).
<br>
• SSTI can happen in two cases:
1) Developer error
2) Intentional exposure of templates to offer better functionality.
<br>

• They can be avoided by whitelisting and sandboxing methods.










