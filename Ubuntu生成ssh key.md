# ubuntu生成ssh key  
生成ssh密钥，中间遇到输入的一直按回车即可
```git
ssh-keygen -t ecdsa
```
查看公钥
```git
cat ~/.ssh/id_rsa.pub
```
将公钥复制粘贴到GitHub的setting——ssh key



