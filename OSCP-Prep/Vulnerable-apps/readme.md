The list of applications I used to practice was:


SLMail: https://www.exploit-db.com/exploits/638/ – The application covered in the OSCP guides. Additional practice can be had with the C code in https://www.exploit-db.com/exploits/646/, this will challenge your understanding of the process, and by making it work – you’ll learn some C!

FreeFloatFTP Server 1.0: https://www.exploit-db.com/exploits/17546/ – I didn’t realise this at the time, but this application actually appears to have many many vulnerabilities in different commands; there could be a lot of practice mileage from this one if you follow the buffer overflow process for each vulnerability that the program has. Exploit-DB knows about quite a few from what I can see.

Minishare 1.4.1: https://www.exploit-db.com/exploits/636/ – Nothing too much to write home about, fairly standard BoF.

Savant 3.1: https://www.exploit-db.com/exploits/10434/ – Straight up BoF once again, but there is a couple of gotchas on this one where you might need to think outside the box.

WarFTPD 1.6.5: https://www.exploit-db.com/exploits/3570/ – This one is olllllllddddd! I tried running it on Windows 7 with Admin privs, enabling compatibility mode, and a few other tricks but every time it would exit with a WinSock error. I ended up having to run it on Windows XP 32 bit to get it to work.
