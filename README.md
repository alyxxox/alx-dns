# alx-dns
```
(IPv4 and IPv6 addresses are the same for all servers, it's the https/tls addresses that specify the server.)

IPv4 Main: 94.140.14.49
IPv4 Secondary: 94.140.14.59
(IPv6 isn't always an option. If it's not, that's okay but if it is, enter it.)
IPv6 Main: 2a10:50c0:0:0:0:0:ded:ff
IPv6 Secondary: 2a10:50c0:0:0:0:0:dad:ff
```
## standard
subtle ad, phishing, malware, etc blocking. It prefers functionality over blocking. Anything connected to the wifi uses this by default.

## secure
extreme blocking, prefers security/privacy over function. I have set up a randomized network interface (i wont be able to tell who the traffic is coming from. it will show up as "router" just like the other server) to use it, you have to manually change your dns addresses to the following:

Recommended to use the Adguard app, if so copypaste the link below into a browser after installing Adguard
```
sdns://AgAAAAAAAAAAAAAaMzI3YmJiMjIuZC5hZGd1YXJkLWRucy5jb20KL2Rucy1xdWVyeQ
```
Otherwise you can use this dns-over-https address when adding the above IPs

dns-over-https: 
```
https://327bbb22.d.adguard-dns.com/dns-query
```
Mac users can alternatively use the below link and install the Adguard profile

https://api.adguard-dns.io/settings/91ac0086-bba2-4590-b0d6-a276a153b07b/doh_mobileconfig.xml

## mobile
the same as the standard server but with mobile optimized blocklists instead, manually adding it gives a more reliable connection as well.

Android users enter the below into the 'Private DNS' option at the bottom of Network settings. 

Private DNS: 
```
7561acdb.d.adguard-dns.com
```

iPhone users, click the link below and press install on the 'Adguard DNS' profile

https://api.adguard-dns.io/settings/4e03f99b-ef8f-4225-9b9c-cf6167e63dc3/doh_mobileconfig.xml
