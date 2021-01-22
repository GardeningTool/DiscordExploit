# Discord-Zeroday
This tool is the result of a vulnerability in Discord's caching system as well as Windows Defender. To put it simply, Discord caches images on the disk, and when the image is written to the disk, Windows Defender scans it. By simply appending a script to the image, you can false flag Windows Defender for anyone who loads the image in. Credits to Foggy for finding this exploit.
