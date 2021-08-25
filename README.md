# CONTROLADOR DE CARGA MPPT DA VOLT

Monitoramento via Zabbix do CONTROLADOR DE CARGA MPPT GERENCIÁVEL da Volt via SNMPv2.

1. Instale o MIB da Volt em seu servidor Zabbix Server ou Zabbix Proxy, ele pode ser obtido acessando a interface web do dispositivo. Se preferir, só baixar a que disponibilizei aqui.
2. Após realizar o Download, adicione o arquivo MIB no diretório destinado a ele. Se sua instalação for no CentOS 7.x, o diretório padrão fica em " /usr/share/snmp/mibs ".
3. Reinicie o daemon do Zabbix-Server ou Zabbix-Proxy a depender por quem o host está sendo monitorando
4. Adicione o mapeamento de valor, caso se faça necessário que está no Template disponibilizado
5. Enfim, importe o Template.




