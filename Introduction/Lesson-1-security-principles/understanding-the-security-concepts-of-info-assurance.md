# Understanding the security concepts of information assurance

Pleae note that for the below diagrams I used ASCII art within a code block to manually draw a triangles as my Markdown editor supports this.

1. CIA Triad (triangle diagram).
2. Methods of Authentication.
3. Non-reudiation.
4. Privacy and Related Laws.

## CIA Triad

I series of terms Confidentiality, integrity and availability. Its for the purpose of information assureance and information security.

       (C) -> Encryption
       /\
      /  \
     /____\

### Confidentiality

Making sure that authorised access to info is protected (info that is sensitive should only be available to suthorised users). The number 1 protection for this is **encryption**.

### Integrity

       /\
      /  \
     /____\ (I) -> Hashing

Making sure systems and data have not been modified by an unauthorised user or threat actor. The number protection to virify integraity is using hashing and shing algorithms

### Availability

          /\
         /  \
    (A) /____\

DDoS -> Botnet.

Making sure systems and data are available at all times to authorised users. Number 1 threat for availability DoS (denial of service) attack or a DDoS (distributed denial of service) in the form of using a compilation of compromised systems often referred to as **botnet**, which is a series of compromised systems or bots that an attacker can control using a command & control or a C2 system.

### Concepts in Encryptions

#### Encryption At-REST

Protecting data in DB or files stored in system.

#### Encryption At-TRANSIT

Two implementations to encrypt data in transit.
(A) -> (B)
Two systems are communicating with each other, i.e. system A is sending dat to system B. To prevent an attacker to steel that data or view the data we can perform **Encryption At-TRANSIT**. Will learn about Protocols like TLS (transport layer security protocol), IPSec and more that allow us to protect data.

#### Encryption In-Process

Whenever we have a program/system processing data and that is encrypting the data to prevent unauthorised access.

## Methods of Authentication

1. Knowledge-based authentication is whenever we use a password, a passhrase, a PIN (personal identification number) or anything we can remember inorder of us to authenticate. This type of authentication by itself is extremely vulnerable to many attacks partically today with many **breaches\*** and cyber attacks, criminals can obtain passwords by crompromising systems and they dump those pw's in the public domain then other attackers use them. This is why we need to employ MFA (multi factor authenication) - using multiple types of authentication.

2. Token-based authentication.
   Using a mobile application to generate a token or code.

3. Characteristics-based authentication.

When we have some kind of Biometrics characteristic like finger print, face recongnition, retina scan etc.
Modern systems employ MFA concepts and is using two or more factors of authentication to make that authentication system stronger i.e. combining password with a token-based, a text message, Characteristics-based authentication or an app running in your phone. The more they use the stronger the authentication system is. However, potentially the lower user experience will be. This is why we need to strike a balance between the number of authentication methods and the user experience.

## Non-repudiation

A legal term that is defined as the protection against an individual that falsely deny having performed a particular action.
This provides the capability to dermine whether a given individual took particular actions, such as you created a particular info, approved info or sent or received a msg.
Today, a lot of these non-repudiation attacks are often in the form of impersonation or spoofing. So a Non-repudiation can also be because of a compromised system, then sending false info or spoofed info to another system.

## Privacy and Related Laws

A privacy is a right of an individual like you to control the distribution of info about about yourself. While
<span style="background-color: lightgray;">security and privacy</span> both focus on the protection of personal and sensitive info, there is a difference. With the increased rate at which data is collected and data is stored across many different industries, pretty much all industries, the push for privacy regulation and compliance has grown significantly. An example of these is the **European Union GDPR** or the General Data Protection Regulation. And that's an example of a law with multinational implications that apply to all organizations, foreign or domestic, doing business in Europe. Now, these laws and regulations dictate that any entity anywhere in the world handling the private data of people in a particular legal jurisdiction must abide by its privacy requirements. As a cybersecurity practitioner, you may not be required to interpret this laws in detail. However, you need an understanding on how they apply to your organization and to you as an individual.
