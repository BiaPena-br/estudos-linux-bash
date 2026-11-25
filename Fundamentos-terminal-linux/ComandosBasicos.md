
# Comandos Básicos

**~** = Diretório home do usuário logado.

**$** =  Mostra que o usuário logado é o comum.

**#** = Mostra que o usuário logado é o root.

**sudo su** = SUPER USER DO  (SUPER USUÁRIO FAZ) SUPER USUÁRIO --- Transforma para o usuário root.

**CTRL L OU clear** = Limpa o terminal.

**exit** = Sai do usuário root.

## Exemplo:

```bash
bianca@DESKTOP:~$ sudo su
[sudo: authenticate] Password:
root@DESKTOP:/home/bianca# exit
exit
bianca@DESKTOP:~$
```
**ANOTA AI:** No user root aparece /home/bianca# pois está no diretório home da user bianca, ai mostra o caminho todo.

**DICA:** Evite ficar logado dentro de root para não rodar um comando destrutivo por engano com poder total.

