# Size Matters

## Question
![image](https://user-images.githubusercontent.com/65474495/146673087-d575c2b2-d3a2-40ac-87fa-72c670bb09d9.png)

## Solution
Firstly we need to convert the ciphertext(c) and n do decimal first using an [online converter](https://www.rapidtables.com/convert/number/hex-dec-bin-converter.html).

Then I googleed how can I decrypt RSA using only c, e, and n. Then I found this online [RSA Cipher Calculator](https://www.dcode.fr/rsa-cipher).
It requires c, e, n and p, q, which I didn't know how to find p & q, but then I scrolled down then it also has a [calculator](https://www.dcode.fr/prime-factors-decomposition) for p and q from public key n.
The result is on the top left:
>![image](https://user-images.githubusercontent.com/65474495/146673635-89b7cb6f-bf2d-43eb-85c5-9534df90c985.png)

The flag is:
> MetaCTF{you_broke_rsa!}
