* __Asterísco *__

Faz referência a uma ou mais letras.

   * Exemplos.: 

      `ls /etc/*.conf`: Exibe todos os arquivos com a extensão .conf do diretório indicado.

---

* __Letra__

   Faz referência a letra indicada no argumento.

   * Exemplos.: 

      `ls /etc/*x*`: Exibe todos os arquivos/diretórios que possuem a letra x (minúsucla) em seu nome;

      `ls /etc/f`*: Exibe todos os arquivos/diretórios, cujo nome começa com a letra f (minúscula).

---

* __Interrogação ?__

   Faz referência a apenas uma letra qualquer.

   * Exemplos.: 

      `ls /etc/?as*`: Exibe todos os arquivos/diretórios, cuja a 2a e 3a letras de seu nome sejam 'a' e 's' respectivamente. A 1a posição do nome pode ser qualquer caractere;

      `ls /etc/???a*`: Exibe todos os arquivos/diretórios que possuem uma letra a (minúscula) na 4a posição do seu nome.

---

* __Chaves { }__

   Fazem referência a padrões de caracteres.

   * Exemplos.: 
      
      `ls /etc/?{am,ul}*`: Exibe todos os arquivos/diretórios, cujo o nome possua um dos padrões, 'am' ou 'ul', a partir do 2o caratere.

      `ls /etc/*{tab,swd}`: Exibe todos os arquivos/diretórios, cujo o nome termine com os padrões 'tab' ou 'swd';

      `ls /etc/*.{conf,db}`: Exibe todos os arquivos/diretórios com a extensão .conf ou .db.

---

* __Colchetes [ ]__

   Fazem referência a faixas de caracteres.

   * Exemplos.: 

      `ls /etc/f[a-i]*`: Exibe todos os arquivos/diretórios, cujo o nome começa com a letra f (minúscula) e a 2a letra está entre 'a' e 'i' (a, b, c, d ,e ,f ,g ,h, i);

      `ls /etc/fp[a-c,e]*`: Exibe todos os arquivos/diretórios, cujo o nome começa com a letra p (minúscula) e a 2a letra está entre 'a' e 'c' (a, b, c) ou é a letra 'e';

      `ls /etc/*[A-D]*`: Exibe todos os arquivos/diretórios que contenham as letras entre 'A' e 'D' (maiúsculas), em qualquer posição de seu nome;

      `ls /etc/[a,e,i,o,u]*`: Exibe todos os arquivos/diretórios, cujo nome comece com vogal (minúscula);

      `ls /etc/?[a,e,i,o,u]???`: Exibe todos os arquivos/diretórios, cuja a 2a letra do nome seja uma vogal (minúscula) e possua 5 caracteres no total;

      `ls /etc/?[am,ul]*`: Exibe todos os arquivos/diretórios, cuja a 2a letra do nome esteja entre 'a' e 'm', ou entre 'u' e 'l';

      _Nas versões mais recentes do Bash, ao utilizar os colchetes, usar duas letras separadas por hífen equivale a usar duas letras juntas._

         Ex.: ```ls /etc/f[a-i]*``` = ```ls /etc/f[ai]*```

---
