# Challenge Description

Given the scenario:

```
HIVE Registration Office is finally hiring a DFIR Candidate all over
the world. Here, they provided you some Windows Artifacts that may 
help you during the analysis.

This will be your first interview!
You should answer the following questions:

* When was the last time this person changed his/her password?
Format: `hh:mn:sc yyyy/mm/dd`

* What is the manufacturer's name of this USER's laptop?
i.e -> `McDonalds`
 
* What is the BIOS Vendor's Name?

* How many times does this user logon?


Flag's format is a combination of all the answers above:
i.e:
`RTL{10:12:13 1991/12/16_McDonalds_Amazon_1337}`

See you on the next interview!
```

The objective of the challenge is to find the corresponding
information based on the task given and the Windows Artifacts.
The main artifacts that will be used here is the `Windows Hive` or
`Windows Registry`.

We can use Registry Explorer Tools or RegRipper which can be retrieved from
Eric Zimmerman's website. He offers a lot of forensic tools that may help us
in this activity. You may download them from this link:
https://ericzimmerman.github.io/#!index.md

After downloaded, you can pass all the registry to the tools.

<img src="images/poc1.png" />

The first question is related to Windows Account Information and it's related to
Windows Security Account Manager (SAM Registry).
