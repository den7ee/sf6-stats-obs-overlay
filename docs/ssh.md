# SSH Cheatsheet

## Criar chave
ssh-keygen -t ed25519 -C "email"

## Ver chave
cat ~/.ssh/id_ed25519.pub

## Testar
ssh -T git@github.com

## Docs oficiais
https://www.openssh.com/manual.html
