## Verify
Firstly i connected to ssh through command `-p 56806 ctf-player@rhea.picoctf.net` and providing the 
password. Then i read the `checksum.txt` file. Then after refering to hints i ran command `sha256sum files/*`.

![Screenshot 2024-11-04 043407](https://github.com/user-attachments/assets/723089d1-9a98-45a2-a0c2-ca712abb51cb)


Now to find the checksum we got in the txt file , i used the command 

`sha256sum files/* | grep' 3ad37ed6c5ab81d31e4c94ae611e0adf2e9e3e6bee55884ebc7f386283e366a4'`
(used the piping concept). Then i got the required file.

`3ad37ed6c5ab81d31e4c94ae611e0adf2e9e3e6bee55884ebc7f386283e366a4 files/e018b574`

Now i just run the file with decrypt.sh file provided.

`./decrypt.sh files/eo18b574`

![Screenshot 2024-11-04 043453](https://github.com/user-attachments/assets/1d0466a1-20e3-43ac-90c4-db9ea4581efb)

## Flag :
`>picoCTF{trust_but_verify_e018b574}`
