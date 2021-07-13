# Engineering_Virtual_Program
Document submitted at the program:

My report on knowledge and findings I gained while cracking passwords provided at this link - https://cdn.theforage.com/vinternships/companyassets/MBA4MnZTNFEoJZGnk/passwd_dump.txt

Learnings and Findings

1.MD5 hashing algorithm was used to protect the passwords.

2.MD5(hash function) protection level is upto 128-bit hash value. It is not used often as it is easy to crack.

3.We can implement SHA-1 (Secure Hash Algorithm 1) instead of MD5 or we can make the password stronger by increasing the combination of upper-lowercase letter, digits, special characters thus making the password length more or equal to 8.

4.Password length used by the organization was between 5 to 14.Uppercase-lowercase letters, digits and underscore were used.(Passwords strength lies between weak to medium).

5.To make passwords harder to crack, password’s length should be more than or equal to 8.Use SHA-1 hashing instead of MD5.Avoid use of names or birth dates in passwords.Use combination of letters, digits and special characters to make password strong.

Cracking passwords
I used Hashcat to crack passwords by using Brute-force attack technique.Also learned about Dictionary-attack.I saved the passwords locally on my system in a file and tried to crack them on my system.Cracked password - johnwick007:f6a0cb102c62879d397b12b62c092c06 can be seen at this link: https://photos.app.goo.gl/NfpLefAcuLFoyMXbA

Resources: 
1.https://hashcat.net/hashcat/ 

2.https://howsecureismypassword.net/ 

3.https://arstechnica.com/information-technology/2013/05/how-crackers-make-minced-meat-out-of-your-passwords/ 

4.https://en.wikipedia.org/wiki/Cryptographic_hash_function
 
