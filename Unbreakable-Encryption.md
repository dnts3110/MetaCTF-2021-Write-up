# Unbreakable Encryption

## Question
![Screen Shot 2021-12-18 at 9 39 00 pm](https://user-images.githubusercontent.com/65474495/146638108-d2161618-68c8-47fa-b571-7483bf3af9eb.png)

## Solution
This question is about one time pad, the basic idea of a one time pad is:
>text XOR pad = ciphertext

>ciphertext XOR pad = text

>ciphertext XOR text = pad

>*Note: XOR is its own inverse.*

Since they gave us the ciphertext 1 and the plaintext 1, to find the pad I used ciphertext XOR text = pad.

Using this [online XOR Calculator](https://xor.pw/#), the result of the pad is:
>27b5e109e1dc2f5868e277dfc4f8d87d94d843b641d48918a5e279e34090c39a86f9117c87a040a4a666b0 in HEX

Now to know the plaintext 2,which contains the flag, using the same website above and ciphertext 2 XOR pad = plain text 2
>![image](https://user-images.githubusercontent.com/65474495/146638795-2ad60aed-96ce-4a17-9631-0f1823c55519.png)
>*Note: We have to add "00" to the end of ciphertext2 as the ciphetext and the keypad has to stay the same length.

The flag is:
> MetaCTF{you're_better_than_steve!}
