# web-offensive-security
Module 15 - Web Application for Vulnerabilities

Command Injection:

![Command Injection-1](https://github.com/ReVampHer/web-offensive-security/assets/98286483/659ea420-6d81-4cc1-91c4-53d29225ce49)

File Inclusion: 

![Command Injection-2](https://github.com/ReVampHer/web-offensive-security/assets/98286483/a3de467a-c377-44db-a3cb-c61884e584c7)


![Command Injection-3](https://github.com/ReVampHer/web-offensive-security/assets/98286483/1a59f452-a545-4a28-9431-f3201d0b78ae)

My Mitigation for Command Injection:
Develop security in the webpage from the backend instead the frontend, for input validation for (numerical) numbers, and periods only for the IP Address.
Store the queries in the database, and call from database with restrictions for input from the user. This is performed as parameterized queries by defining the queries, and later pass the parameters. 

Burp Suite: Brute Force attack:
![Brute Force-1](https://github.com/ReVampHer/web-offensive-security/assets/98286483/34de108d-b752-4abf-b9bd-c9613a177936)


![Brute Force-2](https://github.com/ReVampHer/web-offensive-security/assets/98286483/1d0d2bf3-5c4d-49e0-b25b-19c9cd006115)


![Brute Force-3](https://github.com/ReVampHer/web-offensive-security/assets/98286483/c19ee330-7be1-48d6-aa97-15c2da57dd9e)


![Brute Force-4](https://github.com/ReVampHer/web-offensive-security/assets/98286483/6cf8d5d1-030b-4f77-bd05-8f5eb49f3f1d)


![Brute Force-5](https://github.com/ReVampHer/web-offensive-security/assets/98286483/d1c159e2-e76c-443b-aa53-458b566b4325)


My Mitigation for Command Injection:
End-users would need to make their usernames, and passwords more complex. Option 2 would be to use multi-factored authentication. And my third option to mitigate this vulnerability would be account lockouts after a specified amount of failed login attempts. Additionally, we could monitor the network, and setup firewall protection, just to cover all our bases since we are relying on end-users to… not write their passwords on sticky notes, or place them in text documents, etc.

 The Browser Exploitation Framework (BeEF):

![BeEF-1](https://github.com/ReVampHer/web-offensive-security/assets/98286483/836866e0-31f6-4109-b70b-1362b641aef1)


![BeEF-2](https://github.com/ReVampHer/web-offensive-security/assets/98286483/1ff84931-e01b-4edb-a6d1-2bf649da327a)


![Fake Notification Bar-1](https://github.com/ReVampHer/web-offensive-security/assets/98286483/511fd883-c901-4a81-abd4-33577a24c382)



![Fake Notification Bar-2](https://github.com/ReVampHer/web-offensive-security/assets/98286483/d13ec769-5595-49bb-8943-be3663b2d541)



![Pretty Theft-1](https://github.com/ReVampHer/web-offensive-security/assets/98286483/fca11643-df30-46f2-b5d4-eda0bec81ba3)



![Pretty Theft-2](https://github.com/ReVampHer/web-offensive-security/assets/98286483/2e77b375-cfcd-4369-bff6-f4efd81f7896)



![Host Geo -Third Party-1](https://github.com/ReVampHer/web-offensive-security/assets/98286483/a5d5a243-e5e3-48e4-91a4-ef35b7521871)



![Host Geo - Third Party-2](https://github.com/ReVampHer/web-offensive-security/assets/98286483/71a83581-1153-433b-b1da-9c2d0ad1e27b)



My Mitigation for Command Injection:
Mitigation for stored XSS (cross-site Scripting) using a script (payload) which infects a webpage would be to add server-side input validation to refuse a payload/script. 
We could also you HTTP response headers to prevent a payload from running via transmitting security policies to the browser, and onto the client (user end). 


Resources:

Kimachia, Kihara. “6 Expert Tips on SQL Injection Mitigation and Prevention.” Enterprise Networking Planet, June 2023, www.enterprisenetworkingplanet.com/security/sql-injection-mitigation-prevention.


Helme, Scott. “Hardening Your HTTP Response Headers.” Scott Helme, Sept. 2017, scotthelme.co.uk/hardening-your-http-response-headers.
