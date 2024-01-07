#CTFPDF
-------------------
![](splunk.png)

How to Solve ?
-------------------

- git clone `https://github.com/deadrepo/CTFPdf.git`

- git clone  `https://github.com/openwall/john.git`
- cd Desktop/john/run

Extract the hash of the PDF file 
-------------------
- pdf2john '/home/kali/Desktop/CTFPdf/pay.pdf' > '/home/kali/Desktop/CTFPdf/hash.txt' 

Run John The Ripper 
-------------------
- Use this command `john --wordlist='/home/kali/Desktop/CTFPdf/password_list_v2.txt' --format=pdf '/home/kali/Desktop/CTFPdf/hash.txt'`

Output
-------------------
![](splunk.png)
