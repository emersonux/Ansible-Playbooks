# Playbook para Instalação e configuração do NTP

O mesmo pode ser utilizado em distros RHEL, Debian e Suse like.

Instala e configura o NTP. 

## Observações.
Caso necessite de mais configurações verifique o arquivo de template, pois trata-se do conf.

Caso tenha tenha outros servidores de NTP verifique o arquivo "vars/main.yaml", pois este sobrepoe as variaveis padrão (defaults/main.yaml) que apontam para servidores ntp da internet.