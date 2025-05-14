what is a database:
https://www.techtarget.com/searchdatamanagement/definition/database

What’s the difference between a web server and an app server?
https://www.youtube.com/watch?v=S97eKyv2b9M

What is a DNS server?
https://www.ibm.com/think/topics/dns-server

Single point of failure
https://en.wikipedia.org/wiki/Single_point_of_failure

How do you update your production codebase/database schema without causing downtime?
https://softwareengineering.stackexchange.com/questions/35063/how-do-you-update-your-production-codebase-database-schema-without-causing-downt#answers-header

High Availability Problems
https://docs.oracle.com/cd/E17904_01/core.1111/e10106/intro.htm#ASHIA712

Differences between HTTP and HTTPS
https://www.sectigo.com/resource-library/http-vs-https?utm_source=redirect&utm_medium=tier2&utm_campaign=instantssl

Firewall
https://www.webopedia.com/definitions/firewall/

LAMP (software bundle)
https://en.wikipedia.org/wiki/LAMP_%28software_bundle%29


Load balancing definition:

Load balancing is the process of distributing workloads and network traffic across multiple servers. This process maximizes resource usage, reduces response times, and avoids overloading a single server. It plays an important role in maintaining the performance and stability of servers, databases, and applications.

A load balancer acts as an intermediary between client devices and back-end servers, ensuring that requests are directed to the most appropriate server. This prevents some servers from remaining idle while others are overloaded, helping to ensure optimal resource usage.



How Load balancing works

Load balancing works by analyzing incoming requests and routing them based on specific policies or algorithms. Traffic is then distributed according to different criteria:

Round Robin: requests are sent sequentially to each server in turn.
 
Least Connections: Requests are directed to the server with the fewest active connections.
 
Hash IP: Requests are routed according to the client's IP address to ensure session persistence.
 
Weighted Round Robin: Servers with higher capacity receive more requests.
For more advanced configurations, load balancers can also perform health checks on the servers. These checks ensure that they are responsive and healthy before directing traffic to them, adding a layer of reliability.



What are DNS record types:

DNS record types are records that provide important information about a hostname or domain. These records include the current IP address for a domain.

Also, DNS records are stored in text files (zone files) on the authoritative DNS server. The content of a DNS record file is a string with special commands that the DNS server understands.