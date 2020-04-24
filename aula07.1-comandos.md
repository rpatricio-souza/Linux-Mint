# Comandos Linux

__Os comandos no linux são externos, ou seja, são executáveis salvos em diretórios específicos no /bin__

---

* Abrir o terminal: **Ctrl + Alt + T**

---

* __`cat`: Pega o conteúdo de um arquivo e exibe na tela.__

   * Exemplos: `cat /proc/cpuinfo`

---

* __`cd`: Acessa um diretório.__

   * Exemplos:
   
      `cd /media/rpatricio-souza/Dados`

   * Argumentos comuns:

      `cd /`: Retorna à raiz;

      `cd .`: Aponta para o diretório local. Útil para ser usado com os comandos de cópia/movimentação;
      
      `cd ..`: Volta ao diretório acima;

      `cd ~`: Acessa diretamente o diretório do usuário;
---

* __`clear`: Limpa a tela.__

---

* __`--help`: Argumento que exibe a ajuda de um comando digitado antes do --help.__

   * Exemplos:

      `apt --help`

---

* __`history`: Exibe o histórico dos comandos digitados, onde cada comando tem um índice numérico.__
   
   `!x`: Repete o comando de número 'x' indicado pelo history.

   * Exemplos:

      `!164`

---

* __`ls`: Lista o conteúdo do diretório atual.__
   
   * Argumentos comuns:

      `ls /`: Exibe o conteúdo do diretório passado como argumento.

   * Exemplos:
    
       `ls /media/rpatricio-souza/Dados`

   * Parâmetros comuns:

      `-all`: Exibe os arquivos ocultos;
         
         _No linux, o nome dos arquivos ocultos começam com um ponto: ._

      `-h`: _Human Readable_ melhora a legibilidade, mostrando o tamanho em KB/MB/GB...

      `-l`: Exibe as permissões de cada arquivo/diretório.


---

* __`man`: Abre o manual do comando passado como argumento após o man.
   _O manual traz mais informações que o --help._
   _No Mint, por padrão, o manual vem em inglês, mas pode ser traduzido através do download de pacotes externos._

   * Exemplos:

      `man ls`

---

* __`mkdir`: Cria diretórios.__

   * Exemplos:
   
      `mkdir Teste`

      `mkdir /home/rpatricio-souza/Desktop/Teste`

---

* __`nano`: Editor de texto.__

   _Caso o arquivo não exista, o comando nano cria esse arquivo._

   * Exemplos:

      `nano teste.txt`

   * Comandos comuns (O ^ indicado dentro do editor significa pressionar a tecla Ctrl):

      __Ctrl + o__: Salvar as alterações
      
      __Ctrl + x__: Sair do editor;

---

* __`pwd`: Mostra o caminho absoluto (desde a raiz) do diretório atual.__

---

* __`rm`: Remove arquivos.__

---

* __`rmdir`: Remove diretórios.__

---

* __`touch`: Cria um arquivo em branco.__

   * Exemplos:

      `touch teste`

---