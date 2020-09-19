# Tips For SSRF 🛡️


- How to chain idor to SSRF.
  
  ***Not anything I can think on this line. These are 2 separate lines***

- Any tips for finding SSRF and LFI..?
  
  ***See you will find a dozen of tips on ssrf, lfi, rce, etc but what approach you should follow is to understand how your input is being processed in the backend? Is it interacting with any file system, cloud service, etc ?***

- Any specific mindset for finding SSRF and Information disclosure ?
   
   ***1) Understand how the input parameter is getting processed at the backend or how they could be. 
       2) Look out for APIs which seems to provide some sensitive data, check for misconfigs, idors, etc.***

- Any Tips for SSRF RCE &SQLi
   
   ***Understand how the input parameter is getting processed at the backend or how they could be.***
