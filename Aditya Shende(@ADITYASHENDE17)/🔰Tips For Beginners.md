# Tips for Beginners 🔰
 
- What will you suggest for begginers
 
   ***Rdp at 1st phase***

- books which you have read and found valueable 
And what resources do you use to keep yourself up-to-date
 
   ***All reading about blackhat conf. PDF and slides are available***

- What would be the things you will tell your younger self, when he is starting his bugbounty journey?

   ***Me to younger me: Buddy don’t go for money, you’ll get that but don’t be fast and take care of health***

- When going through targets subdomain list how would we know a particular domain may have bug or show we go through each and every domain(my target has a lot of subdomains)

    ***I always check each and every sub , There is no special power to assume this one is buggy or not***

- How your approach for bug hunting differs for a target which have all assets in scope versus only main application in scope?
Thanks in advance

  ***Scan for each and single target. 1st step to get all urls and check for valid urls. Side by side fuzzing . I do check main application 1st because everyone thinks it’s secure***

- What bugs to focus as a beginner I wanna learn about all the critical bugs but not possible to find it on programs.
Any tips for critical vulns finding?

   ***Always try to find high paid bugs . Rce, ssrf, information disclosure etc. for that you can read slide of blackhat and Hackerone reports***

- When I see a target as "*.site.com " that means that I'm able to hack on that domain and any sub-domain under that domain ? Please help me I'm too confused and also just started my journey.
 
    ***Yes . You can test all domains + subs. And also check oos domains because some subs are in oos***

- We used to follow your achievements steps as easy 1, 2, 3.
  Can you post your recon as that 1, 2, 3?
 
  ***1.Sub domains enum and sorting into live***
 ***2. Wayback , dirsearch, ffuf for brute forcing meanwhile github recon, checking js files. And api ep too***
 ***3. Using known vulns to chain with another bug, Few templates created for nuclei, Function check + exploit.***
 ***4. Burp: Playing with req***

- Finding all parameter seems to be a very good idea for manual testing phase. I just wonder for what else purpose they can be utilized.
 
   ***Xss, ssrf, debug errors, user circumvented vulns(idors), redirections, sometimes rce, oauth bugs etc***

- Also, one question more, I have been ignoring this question for a while, but now I guess I should ask, what does 0days or something like that mean? What's 0 in that? Sorry, This might be the silliest question, but yeah.
   
   ***Zero-day is a bug in software, application, hardware or firmware that is unknown to the party or those who are responsible for it which hits all service who are using the vendor application or software.***
