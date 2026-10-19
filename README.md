# DeadFece-CTF-Keep-Digging-solution


 Created By: `@syyntax` flag{1_l0v3_AI}​‌‌​​‌‌​​‌‌​‌‌​​​‌‌​​​​‌​‌‌​​‌‌‌​‌‌‌‌​‌‌​‌‌‌​​‌‌​​‌‌​​​​​‌‌​‌‌​​​‌‌‌​‌‌​​​‌‌​​‌‌​‌​‌‌‌‌‌​‌‌​‌‌​‌​​‌‌​​‌‌​‌​‌‌‌‌‌​‌‌​‌​​​​​‌‌​‌​​​‌‌‌​​‌​​‌‌​​‌​​​​‌‌​​‌‌​‌‌‌​​‌​​‌​‌‌‌‌‌​‌​​​​​‌​‌​​‌​​‌​‌​‌‌‌‌‌​‌‌​​‌​​​​‌‌​‌​​​‌‌​​‌​​​‌‌​​‌​​​‌‌‌‌​​‌​‌‌‌‌‌​‌

DEADFACE left this calling card on a victim's machine. We suspect there is hidden information in this image, but none of our common steganography tools seem to work. There must be some way to determine where the flag is hidden.

Submit the flag as `deadface{flag-text}`.

[Download Image](https://deadface.sfo3.cdn.digitaloceanspaces.com/2026/challenges/steg/steg06/keep_digging.jpg) SHA256: `12582c19c665ee4c7c8d4517ccb8f3559356620553970b235d8aad4e0b4ff8e2`
![[Pasted image 20261019002058.png]]

![[Pasted image 20261019005931.png]]
![[Pasted image 20261019005953.png]]
![[Pasted image 20261019010111.png]]
![[Pasted image 20261019010402.png]]


шось в файлі там нічо нема, є на завдані скитий текст  flag{1_l0v3_AI}(не підходить)

і невидимий скритий текст:  

  
перетворюєм текст в ASCII і получаєм  

01100110 01101100 01100001 01100111  
01111011 01110011 00110000 01101100  
01110110 00110011 01011111 01101101  
00110011 01011111 01101000 00110100  
01110010 01100100 00110011 01110010  
01011111 01000001 01001001 01011111  
01100100 00110100 01100100 01100100  
01111001 01111101    

це перетворюємо в hex і получаєм  

66 6C 61 67 7B 73 30 6C  
76 33 5F 6D 33 5F 68 34  
72 64 33 72 5F 41 49 5F  
64 34 64 64 79 7D 

це вже декодується як flag{s0lv3_m3_h4rd3r_AI_d4ddy} (цей флаг теж не підходить)

через Ghex ми відкриваєм редактор зображення і міняємо розмір зображеня
02 9E - 670 пікселів в 02 DE - 734 пікселі.




![[Pasted image 20261019011557.png]]
