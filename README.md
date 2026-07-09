# fools_mate
Tryhackme walkthrough 



hello ,

This is a beginner-friendly web application challenge that focuses on understanding HTTP request methods, specifically GET and POST. The challenge is straightforward and can be solved in under a minute with a basic understanding of how web requests work. The only tool required is a web proxy, which is used to inspect and modify HTTP traffic during the assessment.

room link: https://tryhackme.com/room/foolsmate

Firstly we have to connect the machine. Then follow the command




nmap (lab-ip) -sC -sV -T4



<img width="1920" height="1080" alt="nmap" src="https://github.com/user-attachments/assets/48dfe39e-6e2b-49e5-899d-f902ec7b0d5e" />
 fig.1


 when we start the lab machine we can see 2 open ports . After getting into the web page “http://lab-ip” we will have a interface like this


 <img width="1920" height="983" alt="poc" src="https://github.com/user-attachments/assets/5d64f723-0a71-4477-a418-b39507be3cb5" />
 fig.2

 Then open burp suite . Enable the interception then make make a move with rook

 <img width="1920" height="1080" alt="poc1" src="https://github.com/user-attachments/assets/66c9384e-ddc9-4917-a448-379e81fbff85" />
 fig.3

 Then change the position of “to” shown as fig.4

 <img width="1920" height="1080" alt="poc2" src="https://github.com/user-attachments/assets/857b804d-b463-421a-bb40-9eddf21ead20" />
fig.4

Then forward the request . the flag will reflected on the web

<img width="1920" height="1080" alt="poc3" src="https://github.com/user-attachments/assets/aeba53ed-a400-4d59-9cdf-b04171c8e5f6" />



