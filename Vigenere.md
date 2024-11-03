## Vigenere Cipher

Cypher text:
`rgnoDVD{O0NU_WQ3_G1G3O3T3_A1AH3S_f85729e7}`

The cypher given to us is Vigenere cypher. Also the key provided is __'CYLAB'__.

I used the online decoder for vigenere cypher: https://www.dcode.fr/vigenere-cipher.
![Screenshot 2024-11-04 011754](https://github.com/user-attachments/assets/8393d65f-134a-4a7c-84f8-4b58acbbd5ab)

Second apprach would be to do it manually by using vigenere cypher table:

![letter-plaintext-table-Vigenere-cipher-intersection-row](https://github.com/user-attachments/assets/4a067300-df3a-441a-90f0-cae876400000)

Approach would be to use the key as left verticle alphabets column and then cypher text
be the letter in the matrix and then decrypted letter to be the horizontal alphabet row.
Take one letter from cypher at a time with one key letter in order.

### Flag
`picoCTF{D0NT_US3_V1G3N3R3_C1PH3R_d85729g7}`
