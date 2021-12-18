# Unbreakable Encryption

## Question
![Screen Shot 2021-12-18 at 9 39 00 pm](https://user-images.githubusercontent.com/65474495/146638108-d2161618-68c8-47fa-b571-7483bf3af9eb.png)

## Solution
This question is about one time pad, the basic idea of a one time pad is:
>text XOR pad = ciphertext
ciphertext XOR pad = text
ciphertext XOR text = pad

I used [this website](https://hashes.com/en/tools/hash_identifier) to identify the possible hashing/encoding type of that encrypted password.
> ![image](https://user-images.githubusercontent.com/65474495/146637718-4c5b4f34-e9ef-472f-98a3-3deb1a4e2b27.png)
It seems that it use Base64 Encoded String so I used an online [base64 decoder](https://www.base64decode.org/)
> ![image](https://user-images.githubusercontent.com/65474495/146637753-9a2930e1-c6de-4ee2-b96f-6d45280eb030.png)

The flag is:
> MetaCTF{encoding_is_N0T_the_same_as_encryption!!}
