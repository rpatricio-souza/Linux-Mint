* __Asterísco *__

Faz referência a uma ou mais letras.

   * Exemplos.: 

      `ls etc/*.conf`: Exibe todos os arquivos com a extensão .conf do diretório indicado.

---

* __Letra__

   Faz referência a letra indicada no argumento.

   * Exemplos.: 

      `ls etc/*x*`: Exibe todos os arquivos/diretórios que possuem a letra x (minúsucla) em seu nome;

      `ls etc/f`*: Exibe todos os arquivos/diretórios que começam com a letra f (minúscula).

---

* __Interrogação ?__

   Faz referência a apenas uma letra qualquer.

   * Exemplos.: 

      `ls etc/?as*`: Exibe todos os arquivos/diretórios que possuem a 2a e 3a letras com a e s respectivamente. A 1a letra pode ser qualquer caractere;

      `ls etc/???a*`: Exibe todos os arquivos/diretórios que possuem uma letra a (minúscula) na 4a posição do seu nome.

---

* __Colchetes []__

   Fazem referência a faixas de caracteres.

   * Exemplos.: 

      `ls etc/f[a-i]*`: Exibe todos os arquivos/diretórios que começam com a letra f (minúscula) e a 2a letra está entre 'a' e 'i' (a, b, c, d ,e ,f ,g ,h, i).

      `ls etc/fp[a-c,e]*`: Exibe todos os arquivos/diretórios que começam com a letra p (minúscula) e a 2a letra está entre 'a' e 'c' (a, b, c) ou é a letra 'e'.

---
