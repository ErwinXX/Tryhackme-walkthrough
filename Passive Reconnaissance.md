## Task 1
### linux commands :

**whois** to query WHOIS servers

**nslookup** to query DNS servers

**dig** to query DNS servers

### Online services :

**DNSDumpster**

**Shodan.io**

## Task 2
Q1. You visit the Facebook page of the target company, hoping to get some of their employee names. What kind of reconnaissance activity is this? (A for active, P for passive)

ans : ``` P ```

Q2. You ping the IP address of the company webserver to check if ICMP traffic is blocked. What kind of reconnaissance activity is this? (A for active, P for passive)

ans : ``` A ```

Q3. You happen to meet the IT administrator of the target company at a party. You try to use social engineering to get more information about their systems and network infrastructure. What kind of reconnaissance activity is this? (A for active, P for passive)

ans : ``` A ```
## Task 3
![Screenshot 2025-04-27 122854](https://github.com/user-attachments/assets/721f8cc0-60c1-4c78-aced-4fddc925cb8d)

Q1. When was TryHackMe.com registered?

ans : ```20180705```

Q2. What is the registrar of TryHackMe.com?

ans : ```namecheap.com```

Q3. Which company is TryHackMe.com using for name servers?

ans : ```cloudflare.com```

## Task 4

> nslookup OPTIONS DOMAIN_NAME SERVER

OPTIONS contains the query type as shown in the table below. For instance, you can use A for IPv4 addresses and AAAA for IPv6 addresses.

DOMAIN_NAME is the domain name you are looking up.

SERVER is the DNS server that you want to query. You can choose any local or public DNS server to query. Cloudflare offers 1.1.1.1 and 1.0.0.1, Google offers 8.8.8.8 and 8.8.4.4, and Quad9 offers 9.9.9.9 and 149.112.112.112. There are many more public DNS servers that you can choose from if you want alternatives to your ISP’s DNS servers.

![Screenshot 2025-04-27 163456](https://github.com/user-attachments/assets/9ce85bee-95fe-4d62-9ba8-1c49f8da518b)

Q1. Check the TXT records of thmlabs.com. What is the flag there?

![Screenshot 2025-04-27 123400](https://github.com/user-attachments/assets/4a39e8af-ef13-491a-a246-723c6f7be806)

ans : ```THM{a5b83929888ed36acb0272971e438d78}```
## Task 5

Q1. Lookup tryhackme.com on DNSDumpster. What is one interesting subdomain that you would discover in addition to www and blog?

![Screenshot 2025-04-27 155746](https://github.com/user-attachments/assets/e7dd1c17-94fd-4c49-aed3-69ff9efb865e)

ans : ```remote```
## Task 6

Q1. According to Shodan.io, what is the 2nd country in the world in terms of the number of publicly accessible Apache servers?

![Screenshot 2025-04-27 160202](https://github.com/user-attachments/assets/c705bb4c-b1dd-4670-bd52-d9b67deb5fa8)

ans : ```China```

Q2. Based on Shodan.io, what is the 3rd most common port used for Apache?

ans : ```8080```

Q3. Based on Shodan.io, what is the 3rd most common port used for nginx?

![Screenshot 2025-04-27 160303](https://github.com/user-attachments/assets/8a11e9be-0595-4fde-9d2c-fe1cab0954c9)

ans : ```5001```


## Task 7

# Summary

![Screenshot 2025-04-27 164119](https://github.com/user-attachments/assets/2adf5c2b-f93d-4cea-a74a-0f952e0d7ecc)

