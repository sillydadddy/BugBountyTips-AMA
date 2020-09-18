# Recon Tips

- We used to follow your achievements steps as easy 1, 2, 3.
  Can you post your recon as that 1, 2, 3?
 
  ***1. Sub domains enum and sorting into live,2. Wayback , dirsearch, ffuf for brute forcing meanwhile github recon, checking js files. And api ep too,3. Using known vulns to chain with another bug, Few templates created for nuclei, Function check + exploit.,4. Burp: Playing with req***

- How do you approach multiple JavaScript endpoints? (Tools, Flow, methods)?
 
   `https://web.archive.org/cdx/search/cdx?url=*.target.com/*&output=text&fl=original&collapse=urlkey`
          
    ***Multiple tools you can use,In my study OTX, GAU, wayback and gron for sorting helped me alot. Another part I am really weak at xss***

- When approaching a Target, what are first things that come into your Mind that you should hunt for? 
Also, How to not get distracted from other things? (This might be a relative term, but still What points you might consider in General? ) 
Much love
 
   ***Recon is common but view is different. Analysis of js files for information, fuzzing, default urls, understand function etc. If you are very passionate about your target then there is no thing to distract***


- I am on my way to build a fully automated scanner for recon. Common things like finding subdomains, extracting JavaScript, searching for secrets, cvescan, directory  bruteforce, etc already done. What else I can add for better results.
 
  ***Add grabbing all possible parameters , screenshots, redirection payloads, sub domain alert, valid sorting of subs***
