1. Topics Covered: Linux instance, web server, Load Balancer

2. What I understood:-
  a. Web Server :
      1. A web server is a standard server with a web package installed.
      2. It can run on either Windows or Linux operating systems.
      3. To configure any server as a web server, the following steps are essential:
          1. Install the Web Package (HTTPD): This is the software required for the server to handle HTTP requests.
          2. Create a Web Page: Inside the html directory, create a file namedb index.html and add the content you want to display to users.
          3. Start the Web Service: Launch the HTTPD service to make your web content accessible.

  b. Load Balancer :
      1. A Load Balancer distributes incoming traffic across multiple web servers.
      2. It also checks the health of a server and manages the request distribution to the other instances.
      3. This helps to optimize resource utilization and improve response times.
      4. A Load Balancer continuously monitors the health of the web servers. 
         If a server fails a health check, the Load Balancer automatically stops sending traffic to that server 

