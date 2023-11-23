# ubuntu生成ssh key  
生成ssh密钥，中间遇到输入的一直按回车即可
```git
ren@ren:~/3dpointwork$ ssh-keygen -t ecdsa
Generating public/private ecdsa key pair.
Enter file in which to save the key (/home/ren/.ssh/id_ecdsa): 
Enter passphrase (empty for no passphrase): 
Enter same passphrase again: 
Your identification has been saved in /home/ren/.ssh/id_ecdsa.
Your public key has been saved in /home/ren/.ssh/id_ecdsa.pub.
The key fingerprint is:
SHA256:FR24B216Kn3hNb8XsKT2/035FPByxj5n/3+8oCGNYxg ren@ren
The key's randomart image is:
+---[ECDSA 256]---+
|          .+..   |
|          o.+    |
|          .= .   |
|         .o +o*  |
|       ES. =o+oO |
|        + =oo.=.+|
|       . *.+.. =B|
|        . o o..=X|
|           .  .o#|
+----[SHA256]-----+

```
查看公钥
```git
ren@ren:~/3dpointwork$ cat ~/.ssh/id_rsa.pub
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQC831QTauoMFiI/LwXuJh007WigfgBdhX6lgkEh93FzLOnGbcPJnALR0RZaqeh4sa8z1FlqaZkK6eajYSnxA6iZi1urc4bBMIGHHS8ltDqbAcTKYMmoepDDlKEV7VV0LS6XVsX8zDQxlHIlxlv4zDPtkw/y1V1nCcmBE9J88PR9o3Ch0ZeLP5EZngPObtUvI0VI4SHrUQrIdyQKSzG6odU3k1KfvVwe+uiNz3hPkUFF1pRgO3yT5twXeXWHeJRcTdm6fRuKK5v18Opc2oLKFnsDA2KHHPTRu0uKvv6CjvMcZhJHw3P3vnRg77McVlk5FrsefHF7wqbYUQ/NK7ukIS6P ren@ren
```
将公钥复制粘贴到GitHub的setting——ssh key



