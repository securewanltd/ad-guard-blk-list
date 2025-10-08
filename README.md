# **DNS Based Blocklists for AdGuard Home**

This project includes DNS-based blacklists that you can use for AdGuard Home.

* **https://raw.githubusercontent.com/securewanltd/ad-guard-blk-list/refs/heads/main/blk-chat-apps.txt** = This list is for banning chat apps.

## **Usage:**

### for AdGuard Home
Fortigate Firewall can dynamically allocate 131,072 IP addresses. We've divided the list into separate systems for Fortigate. In the scenario above, you can exceed this limit by adding multiple Threat Feeds.

Usage : Filters --> DNS blocklists --> Add blocklists --> Add a custom list --> Enter Name : SECUREWAN BLK CHAT APPS --> Enter a URL ... : **https://raw.githubusercontent.com/securewanltd/ad-guard-blk-list/refs/heads/main/blk-chat-apps.txt**
