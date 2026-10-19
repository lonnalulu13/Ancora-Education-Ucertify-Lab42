# Ancora-Education-Ucertify-Lab42
Observing an MD5-Generated Hash Value

> **Original Lab Source**
> 
> This lab was available through:
>
> [https://ancoraeducation.ucertify.com/app/?func=navigate_items&item_sequence=1]

## Objective of the Lab 
In this lab, you will learn to observe an MD5-generated hash value. MD5 hashing algorithm produces a 128-bit hash value or digest value of an entire file. These hash values can be used for checking the data integrity of the file. When a user downloads any file, the file data can be manipulated by an attacker in between. MD5 gives authentication that the file has been manipulated or not. 
## Instructions 
### STEP 1 
From the left sidebar, click the Terminal icon to open its window. 
### STEP 2 
In the Terminal window, execute the following command to compute and check the MD5 message digest of a downloaded file for errors:
```bash
md5sum ~/Downloads/ucertify.iso > ~/Downloads/temp.txt
```
### STEP 3
In the Terminal window, execute the following command to check the MD5 hash value of the downloaded file and its actual MD5:
```bash
diff ~/Downloads/actual.txt ~/Downloads/temp.txt
```
### Note
* diff stands for difference. This command is used to display the differences in the files by comparing the files line by line.
### STEP 4
You will observe two MD5 hashes.
### STEP 5
Now check both the MD5 hashes. If they are the same, the file is error-free. 
### STEP 6 
Close all windows.

## Disclaimer

This repository is for **educational and personal learning purposes only**.  

The original lab content belongs to **uCertify / Ancora Education** and remains their copyrighted material.  
This repository is not affiliated with, endorsed by, or sponsored by uCertify or Ancora Education.  

No copyright infringement is intended.  
Use of any tools or techniques mentioned here should only be performed in authorized, legal environments.
