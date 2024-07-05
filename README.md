# Trivial-Hacking
A simple method for gaining access to a server.

Suppose you have a website hosted in your server whose login credentials you have forgotten (the scenario looks more legal than others I tried). Now how do you update the website as it would require you to log into the server. I have figured out a way to gain access even in such a tricky situation. Let me explain it as a small tutorial.

your website address: https://www.airtel.in

Step 1.
Copy the website address from the address bar. Suppose it is "https://www.airtel.in".

Step 2.
Use the unix utility https as follows,
>https https://www.airtel.in

on typing return you will get a lot of HTML.

Step 3.
Store all that html into a file say airtel.html by typing the following:
>https https://www.airtel.in > airtel.html

Step 4.
Now comes the real magic (which will be created by you). The html file tha you downloaded is most often than not the index.html file of the website. This index.html file (which is found by typing "https https://www.airtel.in") is the gateway to the whole server. It has links that you can use to go anywhere. Of course wou will have to play around and modify the html first. 
