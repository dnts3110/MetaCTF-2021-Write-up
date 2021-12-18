# Thnks fr th Pwds 

## Question
![image](https://user-images.githubusercontent.com/65474495/146637519-223c0f00-8db0-4cb9-b8e9-a22aec1f8a75.png)

## Solution
I used [this website](https://hashes.com/en/tools/hash_identifier) to identify the possible hashing/encoding type of that encrypted password.
> ![image](https://user-images.githubusercontent.com/65474495/146637718-4c5b4f34-e9ef-472f-98a3-3deb1a4e2b27.png)
It seems that it use Base64 Encoded String so I used an online [base64 decoder](https://www.base64decode.org/)
> ![image](https://user-images.githubusercontent.com/65474495/146637753-9a2930e1-c6de-4ee2-b96f-6d45280eb030.png)

The flag is:
> MetaCTF{encoding_is_N0T_the_same_as_encryption!!}
