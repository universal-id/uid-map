# 🏛 Architecture

The historical architecture of digital system has always involved a centralized identity sub-system system which all other sub-systems are built in top of in the sense of architecture. Only recently has the technology community been working on more distributed identity systems. We want to focus on internet identity and its architectural history.

## 🌐 Systems built on the internet

Internet and the web are essentially public goods, that benefit people across the globe. However, the identity systems that currently help consumers use the web are ultimately private goods, primarily benefiting their providers, as opposed to the actual identity owners. Additionally, these systems are fragmented across multiple centralized providers, including the likes of Facebook, Google, as well as other proprietary solutions.

![Simplified architecture][simple-internet-architecture]

[simple-internet-architecture]: images/simple-internet-architecture.png

The web’s original vision, of a public information system, did not optimize for the use of private information, which in turn led to lack of a robust identity layer in the early Web 1.0 days. Internet companies such as Facebook, Google and Microsoft were driven to build their own identity layers, during the modern Web 2.0 era. These providers have recently adapted their systems into a standards-based identity provider model. Unfortunately this model, though standardized, is not as open, permissionless, and censorship-resistant as the web.

The original internet protocols (TCP/IP, DNS, etc) as well as the world-wide web protocols (HTML, HTTP, etc) were all primarily designed to support a universal information system, one that enabled the sharing and consuming of public information in a decentralized and permissionless manner. It purposefully did not focus on the problem of private information.

Web 1.0 came with its own elementary identity subsystem in the form of Uniform Resource Identifiers (URIs), Domain Name Service (DNS) and X509 secure certificates. These protocols allowed website owners to establish the identity and reputation of their sites online. However, this system was never designed to be a general purpose digital identity system, particularly for consumers of those websites.

The closest the internet came to defining a semi-decentralized and privacy-enabled consumer identity system early in its development, was the Simple Mail Transfer Protocol (SMTP). This system defines identifiers as email addresses and information storage instances as mailboxes, holding user data. However, as per its original design, this system has primarily been specifically been used for transferring email, as opposed to acting as a general purpose identity system.

![Electronic mail identity system][email-identity-system]

[email-identity-system]: images/email-identity-system.png

Facing the above-mentioned lack of a robust universal identity system, Web 2.0 companies such as Facebook, Google and others built their own proprietary identity systems to support their consumer content and social networking platforms. They later evolved their architectures while supporting the general internet community in developing a standardized identity provider model based on OAuth 2.0 and OpenID-Connect set of standards. In the case of Facebook, and a few others, standardized identity systems have been marketed to app developers as a generalized web identity systems, which offer benefits to developers and users, in terms of development and app usability, but at the cost of ceding developer and consumer power to these rapidly growing technology companies.

![Internet detailed architecture][current-internet-architecture]

[current-internet-architecture]: images/current-internet-architecture.png
