# Tips to Approach A target 🎯

- When approaching a Target, what are first things that come into your Mind that you should hunt for? 
Also, How to not get distracted from other things? (This might be a relative term, but still What points you might consider in General? ) 
Much love

   ***Recon is common but view is different. Analysis of js files for information, fuzzing, default urls, understand function etc. If you are very passionate about your target then there is no thing to distract***

- How do you approach a target and any tips for business logic errors
 
   ***Mostly using tools of project discovery for subdomain enumeration,  parsing, sorting into valid one . Subfinder, httpx, shuffledns and nuclei. For finding all urls or path I use wayback. Mostly that helps me to find information disclosure and sometimes unauthorised access.***

-  How do you approach multiple JavaScript endpoints? (Tools, Flow, methods)?
 
              `https://web.archive.org/cdx/search/cdx?url=*.target.com/*&output=text&fl=original&collapse=urlkey`
     
      
   ***Multiple tools you can use , In my study OTX, GAU, wayback and gron for sorting helped me alot. Another part I am really weak at xss***

- 1.How to develop intuition about the type of vulnerability and vulnerable site.
  2. What are the checklist you follow while checking for vulnerability.3. Sir I have found a vulnerability (open redirect) bt.  unable to explain the triage team that how I found it. What to do???
 
    ***There is no specific checklist which I follow. I hunt application as per feature. Instead developing scenario read about techniques and implement while testing. From my point of view I was testing bugs on local sites obviously its not legit but I was curious about learning.***

- How your approach for bug hunting differs for a target which have all assets in scope versus only main application in scope?
Thanks in advance

   ***Scan for each and single target. 1st step to get all urls and check for valid urls. Side by side fuzzing . I do check main application 1st because everyone thinks it’s secure***


- I get annoyed after a while hunting the target.
   1. Can you tell how long and how should I approach a target, so that I can find bugs like you?,2. How to approach a target where there is no auth?
 
    ***If I found target don’t have much more function except register and login, I’ll leave that target. Or else I start to fuzz the same target. Simple rule : no functions no bugs.
 Js files check, source code view for sensitive keywords, dirsearch, ffuf, git recon if target is high***
