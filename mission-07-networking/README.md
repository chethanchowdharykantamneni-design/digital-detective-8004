
# Mission 7 – How Computers Communicate

## 1. Task / Objective

To understand basic networking concepts, check network connectivity, perform DNS lookup and understand how computers communicate when opening a website.

## 2. Work Completed

- Explained LAN, MAN, WAN, DNS, Router and Protocol.
- Understood packet switching and client-server communication.
- Checked internet connectivity using Terminal.
- Performed DNS lookup using nslookup.
- Explained the steps involved in opening a website.

### Task 7.1 – Network Concepts

| Concept | Explanation | Example |
|---|---|---|
| LAN | A network covering a small area. | Home Wi-Fi |
| MAN | A network covering a city. | City-wide network |
| WAN | A network covering large geographical areas. | Internet |
| DNS | Converts domain names into IP addresses. | google.com |
| Router | Connects networks and forwards data. | Wi-Fi router |
| Protocol | Rules used for communication between devices. | HTTP, HTTPS |
| Packet switching | Divides data into small packets for transmission. | Sending files online |
| Client-server | Client requests data and server provides it. | Web browser and website |

### Task 7.2 – Observe Network Information

Commands used:

- `ping -c 4 google.com` – Checks network connectivity.
- `nslookup google.com` – Finds the IP address associated with a domain.

**Questions:**

1. A connectivity test checks whether my computer can communicate with another device or website.
2. DNS lookup displays the IP address associated with a domain name.
3. DNS converts website names into IP addresses so the browser can find the correct server.


### Task 7.3 – What Happens When You Open a Website?

1. I enter a website address in the browser.
2. The browser contacts DNS to find the website's IP address.
3. DNS returns the IP address of the server.
4. The browser sends a request to the server using HTTPS.
5. The request travels through the network and router to reach the server.
6. The server processes the request and sends the website data back.
7. The browser displays the webpage on my screen.

