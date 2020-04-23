# Comandos Linux

__Os comandos no linux são externos, ou seja, são executáveis salvos em diretórios específicos no /bin__

---

Abrir o terminal: **Ctrl + Alt + T**

---

* __cat__

   * Pega o conteúdo de um arquivo e exibe na tela.

   E.: `cat /proc/cpuinfo`

---

* __cd__

   * Acessa um diretório.

   Ex.:
   `cd /media/rpatricio-souza/Dados`

   * Argumentos comuns:

      `cd /`: Retorna à raiz;

      `cd .`: Aponta para o diretório local. Útil para ser usado com os comandos de cópia/movimentação;
      
      `cd ..`: Volta ao diretório acima;

      `cd ~`: Acessa diretamente o diretório do usuário;
---

* __clear__

   * Limpa a tela.

---

* __ls__

   * Lista o conteúdo do diretório atual.
   
   * Argumentos comuns:

      `ls /`: Exibe o conteúdo do diretório passado como argumento.

    Ex.:
    `ls /media/rpatricio-souza/Dados`

   * Parâmetros comuns:

      `-all`: Exibe os arquivos ocultos;
         _No linux, o nome dos arquivos ocultos começam com um ponto: ._

      `-h`: _Human Readable_ melhora a legibilidade, mostrando o tamanho em KB/MB/GB...

      `-l`: Exibe as permissões de cada arquivo/diretório.


---

* __mkdir__

   * Cria diretórios.

   Exs.:
   `mkdir Teste`

   `mkdir /home/rpatricio-souza/Desktop/Teste`

---

* __pwd__

   * Mostra o __caminho absoluto__ (desde a raiz) do diretório atual .
