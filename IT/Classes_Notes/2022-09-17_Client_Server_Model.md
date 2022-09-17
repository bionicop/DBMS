---
creation date: 2022-09-17 16:16
modification date: Saturday 17th September 2022
aliases: [Internet Technologies] 
tags: 
- Internet_Technologies
- Internet_Basics
---

<< [[2022-09-17_Internet_Basics]] | [[]] >>

# ❗❓ Info
Course Name: Internet Technologies
Date: Saturday 17th September 2022
Professor/Speaker: *teach*
Tags: #Internet_Technologies 

---
# 📑 Internet Technologies

## 📃 Summary of Notes
- [Client Server Model](#Client-Server-Model)
	- [Types of Servers](#Type-of-Servers)
- [Protocol](#Protocol)
- 
---
# **Client Server Model**
- The Client-server model is a *distributed application structure* that partitions task or workload between the providers of a *resource or service*, called *servers*, and *service requesters* called *clients*.

## **Type of Servers**

```mermaid
graph TD
    A(Servers) --> B(Application Server) --> 1(Middleware between database server and user.)
    A --> C(Audio/Video Server) --> 2(Multimedia capabilities in web sites.)
    A --> D(Chat Server) --> 3(Enable users to exchange information.)
    A --> E(Fax Server) --> 4(To fax documents.)
    A --> F(FTP Server) --> 5(Move files securely between computers.)
    A --> G(Web Server) --> 6(Deliver web pages.)
    A --> H(Groupware Server) --> 7(Software designed to enable users to collaborate regardless of location via internet or intranet.)
    A --> I(IRC Server) --> 8(Real time discussion capabilities.)
    A --> J(List Server) --> 9(Manage mailing lists.)
    A --> K(Mail Server) --> 10(Move and store mails over internet.)
    A --> L(News Server) --> 11(Distribution and delivery source.)
    A --> M(Proxy Server) --> 12(Between a client and an external server to filter requests, improve performance and share connections.)
```

## **Protocol**
- Protocols are a *fundamental aspect* of *digital communication* as they **dictate how to format, transmit and receive data**. They are a **set of rules** *that determines how* the ==data will be transmitted over the network==.

### **Standard protocols**
- Standard protocols are *agreed and accepted* by the **whole computing industry**. It is **not vendor specific**.

### **Types of Protocol**
```mermaid
graph TD
    A(Protocol) --> B(SMTP)
    A --> C(HTTP)
    A --> D(FTP)
    A --> E(Telnet)
    A --> F(Gopher)
    A --> G(TCP/IP)
```
*and many more..*

## **SMTP**
- SMTP *stands for* **Simple Mail Transfer Protocol**.
- It is an **email communication protocol** that is used by *mail servers* to ==send emails from one account to another via the internet==.
- It uses **port 25**.