# Understanding the security concepts of information assurance

Pleae note that for the below diagrams I used ASCII art within a code block to manually draw a triangles as my Markdown editor supports this.

1. CIA Triad (triangle diagram).
2. Methods of Authentication.
3. Non-reudiation.
4. Privacy and Related Laws.

## CIA Triad

I series of terms Confidentiality, integrity and availability. Its for the purpose of information assureance and information security.

       C -> Encryption
       /\
      /  \
     /____\

### Confidentiality

Making sure that authorised access to info is protected (info that is sensitive should only be available to suthorised users). The number 1 protection for this is **encryption**.

### Integrity

       /\
      /  \
     /____\ I -> Hashing

Making sure systems and data have not been modified by an unauthorised user or threat actor. The number protection to virify integraity is using hashing and shing algorithms

### Availability

        /\
       /  \
    A /____\

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
