# Web-Application-Project-Technical-Brief
    Cybersecurity
Project 1 Technical Brief


Make a copy of this document before you begin. Place your answers below 
each question. This completed document will be your deliverable for Project 1. Submit it through Canvas when you’re finished with the project at the end of the week.


Your Web Application

Enter the URL for the web application that you created:

https://thurgoodsecurityresume.azurewebsites.net/


Paste screenshots of your website created (Be sure to include your blog posts):

![image](https://user-images.githubusercontent.com/105890565/193103290-69ed9fd4-0e82-4a20-9296-df77bbf894da.png)
![image](https://user-images.githubusercontent.com/105890565/193117893-132677ac-fd57-441a-bc63-93b06984b3bf.png)









Day 1 Questions

General Questions

What option did you select for your domain (Azure free domain,  GoDaddy domain)?

Azure Free Domain


What is your domain name?

thurgoodsecurityresume.azurewebsites.net


Networking Questions

What is the IP address of your webpage?

20.118.40.6


What is the location (city, state, country) of your IP address?

Des Moines Iowa USA 


Run a DNS lookup on your website. What does the NS record show?

![image](https://user-images.githubusercontent.com/105890565/193118007-43815eb8-aecd-4dbc-ac7d-8c35fa297f0b.png)



Web Development Questions

When creating your web app, you selected a runtime stack.  What was it? Does it work on the front end or the back end? 

PHP 7.4 
Backend


Inside the /var/www/html directory, there was another directory called assets. Explain what was inside that directory.

CSS & Images files


Consider your response to the above question. Does this work with the front end or back end?

Frontend



Day 2 Questions

Cloud Questions

What is a cloud tenant?

A cloud computing architecture that allows customers to share computing resources in a public or private cloud


Why would an access policy be important on a key vault?

It determines whether a given security principal can perform different operations on Key Vault Secrets, Keys and Certificates 


Within the key vault, what are the differences between keys, secrets, and certificates?

Keys - support key types and algorithms, and enables the use of software-protected and HSM-protected keys
Secrets - provides secure storage of secrets (passwords & database connection)
Certificates - supports certificates and adds an automated renewal feature


Cryptography Questions

What are the advantages of a self-signed certificate?

Self Signed Certificates are useful in test environments and customizable. They also don't rely on others for issuance. 


What are the disadvantages of a self-signed certificate?

They are not vetted and pose risks when compromised. They can be easily revoked.


What is a wildcard certificate?

A wildcard certificate is a single certificate that uses a (*) to allow it to be used to secure multiple sub domain names related to the same base domain.


When binding a certificate to your website, Azure only provides TLS versions 1.0, 1.1, and 1.2.  Explain why SSL 3.0 isn’t provided.

SSL 3.0 was disabled by Azure after many machines and VMs were affected by its safety vulnerabilities for customers. 


After completing the Day 2 activities, view your SSL certificate and answer the following questions:

Is your browser returning an error for your SSL certificate? Why or why not?

No. Because it is certified by Azure 


What is the validity of your certificate (date range)?

March 14, 2022 - March 9, 2023


Do you have an intermediate certificate? If so, what is it?

Yes. Microsoft Azure TLS Issuing CA 


Do you have a root certificate? If so, what is it?

Yes, DigiCert Global Root CA  


Does your browser have the root certificate in its root store?

Yes


List one other root CA in your browser’s root store.

DST Root CA x3



Day 3 Questions

Cloud Security Questions 

What are the similarities and differences between Azure Web Application Gateway and Azure Front Door?

Both reside in front of your web application in order to protect it. 
They work on the Application Layer of the OSI model.
Their primary solution is a load balancer
They can incorporate a web application firewall to protect against web vulnerability attacks.
They have additional features like URL path-based routing and SSL/TLS termination.

The Web Application Gateway is more regional while the Azure Front Door is global and better suited when you have a variety of regions in a cloud environment. 


A feature of the Web Application Gateway and Front Door is “SSL Offloading.” What is SSL offloading? What are its benefits?

SSL offloading is the process of removing the SSL based encryption from incoming traffic that a web server receives to relieve it from decryption of data. 

A benefit is it creates a smoother loading of the website and faster processing of requests at the end of the web application. 


What OSI layer does a WAF work on?

Layer 7


Select one of the WAF managed rules (e.g., directory traversal, SQL injection, etc.), and define it.

A path traversal attack (directory traversal) aims to allow an attacker access to files on your web server to which they should not have access.  


Consider the rule that you selected. Could your website (as it is currently designed) be impacted by this vulnerability if Front Door wasn’t enabled? Why or why not?

No, there are currently no files to be accessed. 


Hypothetically, say that you create a custom WAF rule to block all traffic from Canada. Does that mean that anyone who resides in Canada would not be able to access your website? Why or why not? 

No. They could SSH into a machine with an IP in America and then access the website from that new machine. 


Include screenshots below to demonstrate that your web app has the following:

Azure Front Door enabled

![image](https://user-images.githubusercontent.com/105890565/193118134-6c78e7d3-6da1-44fc-a010-24b799c6a3bc.png)



A WAF custom rule


![image](https://user-images.githubusercontent.com/105890565/193118195-df66af12-d753-488b-ae28-b50473a8ae96.png)



Additional Screenshots of Project


![image](https://user-images.githubusercontent.com/105890565/193118228-02c84691-61fd-46e8-ba9e-097e1c3ac1a7.png)


![image](https://user-images.githubusercontent.com/105890565/193118262-26487ed2-32d0-479b-bbcc-636297f5a3bb.png)

![image](https://user-images.githubusercontent.com/105890565/193118299-d55d096d-9eb2-41ec-902f-093f2cc74bf8.png)

![image](https://user-images.githubusercontent.com/105890565/193118341-68e7bdcf-8d85-4548-a457-f3016ec90249.png)

![image](https://user-images.githubusercontent.com/105890565/193118377-a39c2a01-729c-44b0-a26f-916974e9096d.png)

![image](https://user-images.githubusercontent.com/105890565/193118407-001002fd-3e0b-4ed1-ad48-46a985808a8d.png)




© 2022 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.

