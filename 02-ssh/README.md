# Section 2: SSH

Task: Set up SSH on github account

## Introduction

SSH is secure shell protocol

Example of protocols:

* HTTP - Hyper Text Transfer Protocol (Alows to send files over the intenet, likes HTML, CSS and JS, between browsers and servers)
* FTP - File Transfer Protocol (Often use to upload file to server)
* HTTPS - Hyper Text Transfer Protocol Secure - Encrypted HTTP
* SSH - Is protocol that alows us to comunicate between two computers over the intenet. It alows users to share files, control and modified an remote computer over the internet. This is secure ways of comunication witch encrypt all data. Comunication shell

CLIENT <- Secure Shell Protocol -> HOST

## SSH Command

```bash
ssh {user}@{host}
```

Example

```bash
ssh root@167.99.146.57
```

Example of use SSH:

* Connecting to github (clone, push, push, ..)
* Remotly access to other computer
* Access to production server (get back up app)

### Resources: SSH Command

<https://www.makeuseof.com/tag/beginners-guide-setting-ssh-linux-testing-setup/>

### How SSH Works

Encrypting technics:

* Symmetrical
* Asymmetrical
* Hashing

#### Symmetrical Encryption

Use one secret key for encryption and decryption.

#### Asymmetrical Encryption

Use two separate keys pairs (public and private) for encryption and decryption.

Resources: Asymmetric Encryption
<https://www.youtube.com/watch?v=NmM9HA2MQGI>
<https://www.youtube.com/watch?v=Yjrfm_oRO0w>
<https://www.youtube.com/watch?v=vsXMMT2CqqE&t=>
<https://www.youtube.com/watch?v=NF1pwjL9-DE>

#### Hashing

#### SSH into a server

Recommended ssh-keygen command:

```bash
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
```
