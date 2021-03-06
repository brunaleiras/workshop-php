# Instalação

## Linux
Instalar o PHP no Linux é muito simples! Você deve primeiro abrir o terminal. Para isso você pode pesquisar nos seus programas instalados ou se preferir com o seguinte atalho:
ctrl + alt + t

Com o terminal aberto digite:

```bash
sudo apt install php
```
###### Obs.: em um sistema baseado em Debian usa-se apt para instalar pacotes.  

Desta forma o PHP será instalado no seu computador.

Para conferir a versão instalada digite:

```bash
php -v
```
  
Pronto! O PHP está pronto para ser utilizado.

## MAC
Instando PHP no MAC - via Macports

O projeto MacPorts é uma iniciativa da comunidade de código aberto para projetar um sistema fácil de usar para compilar, instalar e atualizar softwares por linha de comando.

Você pode instalar o php em diferentes versões : php5.4, php5.5, php5.6, php7.0, php7.1, php7.2 ou php7.3 usando o comando port install, como no exemplo abaixo:

```bash
sudo port install php56
sudo port install php73
```

Você pode utilizar o comando select para trocar a versão ativa do PHP:

```bash
 sudo port select --set php php73
```

[Voltar a página inicial](../README.md)
