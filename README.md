
# Domain Name System (DNS)


There are many ways to identify a person uniquely
Eg:Passport,Aadhar no etc. 

Similarly IP adress is used to identify a host/router uniquely.

Lets say I have my enterprise application server at an IP address. But the world knows it as "sup123.com".

How do I map this name with my IP address?

Thats the job of DNS.It is an application layer protocol to provide mapping between domain names and IP addresses.






## Mapping
#### Manage DNS records:

Go to manage dns records section of you domain registrar's site.

Delete all default records.

![](https://user-images.githubusercontent.com/91104162/217019065-8bf104e6-67e8-4975-a5de-98972bf5f790.png)

Set up 4 records as shown above

Type A resolves to IPV4 address
Type AAAA resolves to your IPV6 address

www, @ make it both available at  w ww.xyz.com as well as xyz.com

You can refer your IP adresses from your vps/shared server's access details.

And your mapping will be done!!

## Key Concepts

#### Heirarchy of DNS
![](https://user-images.githubusercontent.com/91104162/217018988-14e10cd7-3656-4b02-8017-b40aad64b999.jpg)

#### DNS name resolution
(2 approaches)
#### Iterative
![](https://user-images.githubusercontent.com/91104162/217021676-5e9ffe2e-beb8-46e3-b5fd-65ddfae9589b.jpg)

#### Recursive
![](https://user-images.githubusercontent.com/91104162/217021676-5e9ffe2e-beb8-46e3-b5fd-65ddfae9589b.jpg)


