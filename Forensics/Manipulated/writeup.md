# Challenge Description

Given the description of the challenge:
```
There's a breach in CIA Office this morning. Someone has just 
manipulated the photo of our confidential documents so that
we can't open it. Luckily, the perpetrator didn't change the
image's checksum.

The major told us to recover the image as soon as possible before
he arrives here. Can you recover it back?
```
You can download the challenge from the chall folder.
The objective of the challenge is to recover the corrupted image because of
manipulated IHDR Chunk where the PNG's dimensions are altered.

The POC can be viewed from `pngcheck` tools and your Hex Editor's preferences.
