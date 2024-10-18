## Terminal Linux (Shell)

- **Shell**: Software que roda dentro do terminal e interpreta os comandos que você digita.
- **Terminal**: Interface gráfica ou de texto que permite interagir com o Shell.
  
### Resumo

- **Terminal**: A janela onde você digita comandos.
- **Shell**: O programa que interpreta e executa os comandos no sistema.

---

## Comandos Padrões do Terminal

- **`sudo`**: Superusuário; permissões elevadas para executar comandos.
- **`$`**: Usuário comum, sem permissões elevadas.
- **`Root`**: Superusuário.
- **`#`**: Usuário que pode fazer tudo.

---


# Comandos Básicos do Linux

## Navegação e Listagem

- **`ls`**: Lista pastas e arquivos no diretório atual.
- **`cd <pasta>`**: Muda para o diretório especificado. Você pode selecionar pastas de qualquer lugar usando o comando:
  - Exemplo: `cd /home/paulo`
- **`cd ..`**: Volta um diretório acima.

---

## Comandos de Administração

- **`sudo`**: Executa comandos como superusuário (modo ADM).
- **`sudo apt`**: Usado para atualizar e instalar programas:
- **`sudo apt install <pacote>`**: Instala um ou mais pacotes específicos que você deseja baixar. É possível listar vários pacotes na mesma linha, separando-os por espaços.
- **`sudo apt update`**: Atualiza a lista de pacotes disponíveis.
- **`sudo apt upgrade`**: Atualiza todos os pacotes instalados.
- **`sudo apt full-upgrade`**: Força a atualização completa do sistema.
- **`sudo apt dist-upgrade`**: Força a atualização do kernel (sistema operacional).
- **`sudo apt autoremove`**: Checar Softweres desnecessarios e remover.
- **`sudo apt autoclean`**: Limpar o Cache do apt
- **`sudo dpkg -i <pacote.deb>`**: Instala um programa baixado pelo navegador.
- **`mkdir <nome_da_pasta>`**: Cria uma nova pasta.
- **`rmdir <nome_da_pasta>`**: Remove uma pasta (apenas se estiver vazia).
- **`rm <nome_do_arquivo>`**: Remove arquivos.
- **`rm -r <nome_da_pasta>`**: Remove uma pasta e todo o seu conteúdo.

---

## Comandos Úteis
- **`sudo reboot`**: Reiniciar a maquina
- **`sudo poweroff`**: Desligar a maquina
- **`whoami`**: Exibe o nome do usuário atual.
- **`clear`**: Limpa a tela do terminal (ou `CTRL + L`).
- **`pwd`**: Mostra o caminho do diretório atual.
- **`touch <nome_do_arquivo>`**: Cria um arquivo vazio.
  - Exemplo: `touch paulo.txt`
- **`nano <nome_do_arquivo>`**: Abre um arquivo para edição.
- **`cat <nome_do_arquivo>`**: Lê o conteúdo de um arquivo de texto sem abrir um editor.
- **`<comando> --help`**: Mostra as funções e opções disponíveis para um comando.
  - Exemplo: `sudo --help`
- **`history`**: Mostra o historico de comandos utilizados
---

## Conceitos Básicos

- **`~`**: Representa o diretório HOME do usuário.
- **`ROOT`**: Referência ao usuário administrador (superusuário).

---

## Atalhos do Linux

- **`Shift + CTRL + V`**: Copiar texto no terminal.
- **`Ctrl + Alt + F1`**: Acessar TTY (Terminal de Texto) para usuários diferentes na mesma máquina ao mesmo tempo(F1-F12).
- **`Ctrl + Alt + F7`**: Retornar ao ambiente gráfico padrão.
- **`Ctrl + D`**: Sair de uma aplicação.
- **`Ctrl + alt + Backspace`**: Reinicia apenas o ambiente grafico.
- **`Tab`**: Completa o restante do comando.
