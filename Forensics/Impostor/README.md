# Challenge Description

Given the scenario:
```
Aseng, a fresh-graduate who just lands his first job as an intern in
`Weeb Company` , has just been fooled by someone inside the
office. A day before the incident happened, he received a message from
his office's partner who turns out to be a fraud and surprisingly
that guy is from the **insiders**, the same work-faculty.
The fraud sent him a file from gofile.io and fooled him to run a fake 
Windows Service (Service Host Process).

Aseng was phished and social-engineered that the fraud successfully got
his password already from social-media. Unfortunately, the CCTV inside the
work office has been turned off since last week. Aseng was told to do 
some kind of memory dump of his office's laptop so that you, as an Office's
Incident Responders can investigate what kind of malicious activity does
the fraud do and what activity that triggers Aseng to send his password to
the fraud.

Link to access the file:

https://mega.nz/file/MYJ1BS5S

Decryption Key:
`GmXuj54yEHXxk6peslvJyH0m830A3ogdWkRPxhYHaOE`
```

You can download the challenge from the MEGA link. We are given a memory forensics challenge
where the objective of it should be investigation analysis. 
We can use `Volatility` tools which can be downloaded from this Github:
https://github.com/volatilityfoundation/volatility

I'd still strongly recommend to download Volatility 2 instead of Volatility 3 due to
its several plugins limitations.

We can use `imageinfo` or `kdbgscan` plugin in order to retrieve the OS Profile of the challenge.


