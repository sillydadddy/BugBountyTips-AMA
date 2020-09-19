# Tips for Fuzzing 🌀

- Tips for fuzzing ?
 
   ***It depends on what you need to fuzz, however most of the times I am using Burp Intruder with the hex payloads starting from 00 to FF with prefix %***


- Why hex payloads?
 
   ***They are URL encoded ASCII characters, nearly similar sending all characters one by one with wordlist. Sometimes also URL decode the payloads for different results, if it is a relevant one.***

