Day 1 Task

Writeup :- SSRF 


https://infosecwriteups.com/story-of-a-really-cool-ssrf-bug-cf88a3800efc


https://medium.com/@shahjerry33/blind-ssrf-the-hide-seek-game-da9d0ecef2fb


SSRF Tip by Shah Jerry


When testing for Blind SSRF it is common that you’ll find a DNS lookup for the given Burp Collaborator domain, but no HTTP request. This happens because the application 
attempted to make HTTP request to domain, which caused initial DNS lookup but the actual HTTP request was blocked by the network-level filtering.If you find only 
the DNS lookup or DNS query then it is not a vulnerability, it is mandatory to have the HTTP response which will make it a valid vulnerability.


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Red Team :- https://youtu.be/EIHLXWnK1Dw by 


@HackerSploit
