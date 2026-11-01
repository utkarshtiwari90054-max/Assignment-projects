# Assignment 1.1 — How a Website Works

## 1. How a Website Works (Explanatory Paragraph)

When a user enters a URL (Uniform Resource Locator) in a web browser such as Google Chrome, the browser acts as a client and sends a request to the web server through the internet. First, DNS (Domain Name System) converts the domain name into an IP address so that the browser can locate the server. The server receives the request, processes it, and may communicate with a database to retrieve the required information. The server then sends a response back to the browser using HTTP (Hypertext Transfer Protocol) or HTTPS (Hypertext Transfer Protocol Secure). HTTP is used to transfer data between the browser and server, whereas HTTPS provides secure and encrypted communication. This complete process is called the request-response cycle. Finally, the browser receives HTML, CSS, JavaScript, images, and other resources, processes them, and displays the website on the screen.

## 2. Basic Roles of Website Components

**1. Browser:** A browser is software used to access and display websites. Examples: Google Chrome, Mozilla Firefox, and Microsoft Edge.

**2. Client:** A client is a device or application that sends requests to a server. A web browser works as a client.

**3. Server:** A server is a computer or software that receives client requests, processes them, and sends responses.

**4. Database:** A database is an organized collection of information used to store and manage data, such as usernames, passwords, and student records.

## 3. Meaning of HTTP and HTTPS

**HTTP:** Hypertext Transfer Protocol. It is a communication protocol used to transfer data between a browser and a web server.

**HTTPS:** Hypertext Transfer Protocol Secure. It is the secure version of HTTP that uses encryption (TLS) to protect data transferred between the browser and server.

## 4. Request-Response Cycle

The request-response cycle is the process through which a client communicates with a server.

Steps:

1. The user enters a website URL in the browser.
2. The browser finds the server's IP address using DNS.
3. The browser sends an HTTP/HTTPS request to the server.
4. The server receives and processes the request.
5. The server communicates with the database if required.
6. The server sends an HTTP response to the browser.
7. The browser processes the received files and displays the website.

## 5. Difference Between Static and Dynamic Websites

| Static Website | Dynamic Website |
|---|---|
| Displays fixed content. | Displays changing content. |
| Content usually remains the same for every visitor. | Content can change according to users or data. |
| Generally uses HTML and CSS. | Can use HTML, CSS, JavaScript and server-side technologies. |
| Usually does not require a database. | Often uses a database. |
| Faster and simpler to develop. | More complex to develop. |
| Example: Simple portfolio page. | Example: Facebook, Amazon, and online banking websites. |

## 6. Practical: Inspecting Requests Using Chrome DevTools

**Objective:** To inspect website network requests using Google Chrome Developer Tools.

**Procedure:**

1. Open Google Chrome.
2. Visit any website, for example: https://www.wikipedia.org
3. Right-click anywhere on the webpage.
4. Select Inspect.
5. Open the Network tab.
6. Refresh the webpage by pressing Ctrl + R.
7. Observe the different network requests.
8. Click on any request to see its details.
9. Take a screenshot of the Network tab.

**Important observations:**

- Name: Name of the requested file or resource.
- Status: HTTP response status code.
- Type: Type of resource (document, script, image, stylesheet, etc.).
- Initiator: What caused the request.
- Size: Size of the transferred resource.
- Time: Time taken to complete the request.

## 7. Conclusion

A website works through communication between a client and a server. The browser sends requests, the server processes them, and the server returns responses. HTTP and HTTPS are communication protocols used for transferring information. Static and dynamic websites differ in how they display and manage content. Chrome DevTools helps developers inspect network requests and understand how websites work.