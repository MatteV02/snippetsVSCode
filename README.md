# Snippets VSCode for "Sistemi Operativi"

## Direct contributors
- [MrBigSlime](https://github.com/MrBigSlime)
- [MatteV02](https://github.com/MatteV02)

## Observers
- [SaverioNapolitano](https://github.com/SaverioNapolitano)
- [laurartt02](https://github.com/laurartt02)

## Content
The repository contains repeated code in the exercises in the repo [SoeLab-PrimaFile](https://github.com/MatteV02/SOeLab-PrimaFila) useful for the exam "Sistemi Operativi e laboratorio" of the University of Modena and Reggio Emilia.

## How to setup in VSCode
1. If not installed, install git: open terminal then launch
```bash
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install git
```
2. clone this repo into VSCode snippets folder: launch
```bash
git clone https://github.com/MatteV02/snippetsVSCode.git ~/.config/Code/User/snippets
```
3. Make a link on the desktop
```bash
ln -s ~/.config/Code/User/snippets $HOME/Desktop/VSCode-snippets
```
4. make a bash script to syncronize the folder
```bash
echo '#!/bin/sh' > $HOME/Desktop/syncSnippets.sh
echo 'cd ~/.config/Code/User/snippets' >> $HOME/Desktop/syncSnippets.sh
echo 'git pull' >> $HOME/Desktop/syncSnippets.sh
chmod u+x $HOME/Desktop/syncSnippets.sh
```
    - RUN this script frequently