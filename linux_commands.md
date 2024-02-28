![Tux](https://github.com/ElmarUhl/ElmarUhl/assets/157088447/95cb91c8-c657-4371-9ded-5fdecec6d367)

# Linux Usefull Commands

- ```(command) | more``` faz página em um comando
- ```time program_name``` to shows the time spents running a program
- ```ping 142.250.65.196``` shows IP acess times (the IP number is from google.com)
- ```sudo systemctl disable bluetooth.service``` on/off bluetooth
- ```alt + tab``` change among running programs
- ```cat /etc/os-release``` Operational System information
- ```cat /proc/cpuinfo``` shows cpu cores information
- ```sudo apt search package_name``` shows packages
- ```sudo apt clean``` clean the repositories
- ```sudo apt autoremove``` remove orfan packages
 
- ```gpg --gen-key``` generate private and public keys
- ```gpg --full-generate-key``` full dialog to generate keys
- ```gpg -e file.txt``` - encrypt file
- ```gpg -e -a file.txt``` - encrypt files ASCII
- ```gpg -r key -e file.txt``` - encrypt file with external public key
- ```gpp -d file.txt.gpg``` or ```gpg -d file.txt.asc``` - desencrypt
- ```gpg -s file.txt``` - sign compacted file 
- ```gpg -s --clear-sign``` - sign file
- ```gpg --verify file``` - verify sign
- ```gpg --export -a usuario``` - export public key
- ```gpg --import chave-pub-usuario.txt``` - import key
- gpg --list-keys
- gpg --list-secret-keys
- gpg --delete-key usuario
- pg --delete-secret-key usuario

# Linux Global References

- \* - any sequence of characters
- ? - any single character
- [a-z] - single character between a and z
- [a,e,i,o,u] - a single character vogal
- {abc, cde} - sequences abc or cde

# Programs

- tesseract : OCR
- pwgen : gerador de senhas
- metapixel : cria foto mosaicos
- pandoc levine.odt -o levine.tex : converte entre formatos de arquivo
- ghdl : compilador hdl
- gbr2ngc : gera gcode de arquivos gbr (Corel Draw)
- drl2gcode : gera gcode de arquivos drl
- dmap2gcode - gera mapas de altura de imagem em gcode
- synaptics : linux packages administration
- gparted : disk partition mananger
