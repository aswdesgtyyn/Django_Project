# Answers to the Questions

**Q: What actually happens, step by step, when you type a URL into your browser and hit Enter?**

> **Answer :**
> 1. Browser sends a request to the DNS Server to get the IP Address corresponding to the URL.
> 2. After Reciveing the IP Address the Browser then sends an HTTP request to the Website, Asking for the webpage.
> 3. The Server of the Website then sends the contents of the webpage to the browser with a "200 OK" message.
> 
> _Note: The Data is sent in small payloads called Packets_
>

---
**Q: What are the client and the server, and how do they talk to each other?**
> **Answer :**
>  - Client is the device which requests a reasource from a server like a webpage, picture, video, etc.
>  - Server is the device which gets the reasource and sends it to the Client.
>  - They Talk to each other using TCP and IP to send packets to each other.
>

---
**Q: What is HTTP? What's inside a request and a response?**
> - HTTP is Hyper Text Transfer Protocol is communication protocol that helps clients and servers transfer web reasources like webpages, images, etc
> - In a Request
>    1. HTTP Method 
>    2. HTTP Version
>    3. HTTP Headers
>    4. Request Body
>    5. The HOST
>
> - In a Response
>    1. HTTP Version 
>    2. HTTP Status Code 
>    3. HTTP Headers 
>    4. Response Body 

**Q: What's the difference between GET and POST, and when would you use each?**
> **GET Method**
> - Get Requests requests some resource from the server.
> **POST Method**
> - Post sends some data to the server for it to save.
>
> Both are different as one (POST) is used to send data to server whereas one (GET) is used to request some data from the server.
---
**Q: What do status codes like 200, 302, 404 and 500 mean?**
> - 200 (OK): Means request succeeded
> - 302 (FOUND): Means the resource has been temporarily moved and redirects to it.
> - 404 (NOT FOUND): Means the requested resource was not found.
> - 500 (INTERNAL SERVER ERROR): Means that the server encountered a generic error while executing the request.

---
**Q: What jobs do HTML, CSS and JavaScript each do on a page?**
> - HTML : Defines different elements and content of a webpage and sturture of the webpage.
> - CSS  : Adds the Style of the webpage (Colours, Borders, Backgrounds, etc)
> - JS   : Adds Functionality to a Webpage (Scripts, Interative Elements, etc)

---
**Q: How does a website remember who you are between pages? (Look up cookies and sessions.)**

---
**Q: In Django, how does a request travel through URLs, views, models and templates before a response comes back?**

---
**Q: Why did the tutorial add {% csrf_token %} to the voting form?**
