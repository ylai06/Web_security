## SQL injection

## Cookie 
A cookie attack in web security refers to various malicious activities aimed at exploiting vulnerabilities in the way web applications handle cookies. Cookies are small pieces of data stored on a user's browser that are used to store information such as session identifiers, user preferences, and other data relevant to the user's interaction with a website. Here are some common types of cookie attacks:
### 1. Session Hijacking (Session Cookie Theft)
- Attackers may intercept and steal session cookies to impersonate a user and gain unauthorized access to their account. This is often achieved through techniques like session sniffing or session sidejacking.
### 2. Cross-Site Scripting (XSS)
- If a web application is vulnerable to XSS, attackers can inject malicious scripts into the application, and these scripts may be used to steal cookies from other users.
### 3. Cross-Site Request Forgery (CSRF)
- In CSRF attacks, a malicious site tricks a user's browser into making a request to a target site where the user is authenticated, potentially leading to actions being taken on the target site without the user's consent.
### 4. Cookie Poisoning
- Attackers may tamper with cookies by modifying their values or injecting malicious content. This can lead to various security issues, such as privilege escalation or unauthorized access.
### 5. Man-in-the-Middle (MITM) Attacks
- In a MITM attack, an attacker intercepts communication between a user and a website, allowing them to eavesdrop on or manipulate the data, including cookies.

### To mitigate cookie attacks, web developers and security professionals employ various security measures, such as:
1. **Secure Cookies:** Using secure and HTTP-only flags for cookies to prevent them from being accessed through insecure channels or manipulated by client-side scripts.
2. **HTTPS:** Encrypting the communication between the client and server using HTTPS to protect data from being intercepted in transit.
3. **SameSite Attribute:** Specifying the SameSite attribute in cookies to control when cookies are sent in cross-site requests, thereby preventing CSRF attacks.
4. **Regular Security Audits:** Regularly auditing and testing web applications for security vulnerabilities to identify and address potential weaknesses before attackers can exploit them.



## Insufficient Logging
### 1. Vim cache leak (緩存洩漏)
- When developers use the vim editor in an online environment, the vim editor cache will be left during use. When vim exits abnormally, the cache will remain on the server, causing the website source code to be leaked.
