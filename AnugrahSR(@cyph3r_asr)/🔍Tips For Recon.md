# Tips For Recon 🔍

- Steps for recon..?
 
   ***It's have almost all the things I do. Sometimes I just skips things and just collect subdomain and run scanners to get easy stuffs.
 Mindmap taken from [Rohit Gautham](https://youtu.be/z24ELkocsJE)***

- favorite recon tool ??
 
   ***Osmedues and nuclie***

- After all the recon, how do you find that "Yeah! I must start with this"?
 
   ***What I usually do is, get a list of subdomains, screenshot it. If it have a login panel or seems interesting will look at that.Or take subs one by one and run ffuf. I have got into unauthendicated admin panels like this. Then check for rate limits, password reset, auth misconfig***


- Do you perform directory brute force in your recon methodology? If yes, when do you feel like ‘yeah now I’ve to perform directory brute force on this endpoint’ ?
 
   ***When I have a list of subdomains, I usually screenshot websites with aquatone and open each websites and run ffuf or dirseach on that. Running directory bruteforce have allowed me to find simple phpinfo files to access to admin panel. I want to try making custom wordlist oneday***

 
- What wordlist you use for ffuf permutations subdomain bruteforcing

  ***Subdomin bruteforce: I use commonspeak + all.txt Permutations.I use the buildin wordlist itself in altdns or dnsgen.Dirseach generic wordlist***
