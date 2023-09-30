ansible-fedora-desktop: configurar um desktop Fedora 

## Objetivo

Configurar um desktop Fedora, usando o Plasma como ambiente de desktop, com as ferramentas que uso no meu dia-a-dia profissional e pessoal. 

## Uso

Como é preciso permissão de root: 

    $ ansible-playbook -K config-desktop.yml

## Configurações realizadas
### Atualmente:
* Instalar o KDE Plasma e configurar o gerenciador de login como sendo o sddm

### Futuramente:
* Ativar repositórios extras
* Instalar a "stack" padrão para uso pessoal/desktop (LibreOffice, GIMP, Inkscape, VLC, alguns outros)
* Instalar, via flatpak, alguns softwares proprietários (Discord, Zoom, Steam, Spotify)
* Instalar ferramentas de desenvolvimento (git, vim, vscode, gcc etc...)
* Instalar algumas ferramentas em linha de comando (tmux, weechat, vim, zsh)
* Instalar jogos/emuladores (nethack, MAME, DOSBox, snes9x)

A partir daqui, o desktop já estará em uma condição inicial na qual é possível restaurar os backups da /home e sair usando, talvez sendo necessário algum ajuste pontual.

## TODO

* Verificar uma forma de evitar o uso de `--ask-become-pass`.
