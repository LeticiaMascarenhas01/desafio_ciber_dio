# desafio_ciber_dio
Desafio de ciber segurança da DIO

Ferramentas: Kali Linux/setoolkit

Configurando o Phishing no Kali Linux
Acesso root: sudo su
Iniciando o setoolkit: setoolkit
Tipo de ataque: Social-Engineering Attacks
Vetor de ataque: Web Site Attack Vectors
Método de ataque: Credential Harvester Attack Method 
Método de ataque: Site Cloner
Obtendo o endereço da máquina: ifconfig

URL para clone: http://www.facebook.com

![Captura de tela 2025-01-18 234037](https://github.com/user-attachments/assets/d4b60d5d-2dd7-4b2f-9b4f-23386a18be0b)
![Captura de tela 2025-01-18 234013](https://github.com/user-attachments/assets/8a1023e8-1316-44f3-b95f-79025b35a551)
![Captura de tela 2025-01-18 233956](https://github.com/user-attachments/assets/bb9f4b0e-cdca-47b1-85c7-01d1b4ec5f8d)
![Capturar](https://github.com/user-attachments/assets/7f366261-e098-432f-9570-ba53f5717e43)
![Captura de tela 2025-01-18 234303](https://github.com/user-attachments/assets/d368a74e-9f9d-4f65-b9d6-c9b104899292)
![Captura de tela 2025-01-18 234236](https://github.com/user-attachments/assets/13a78d9b-8cad-4cdb-9ac8-a6fc73c56a1e)
![Captura de tela 2025-01-18 234141](https://github.com/user-attachments/assets/1ae6d60b-d1ae-4d4c-8794-a9f2bb8cb6d5)


Passo a passo para a realização do desafio:

1- caso seja necessário modificar o usuário para root, se utiliza "sudo su", enter, senha padrão do kali e entramos como root
2- após isso é necessário ativar a ferramenta setoolkit usando "sudo setoolkit", enter e pronto
3- opção "website attack vectors" ou opção padrão "2"
4- opção 3 ou "credential harvester attack method"
5- opção 2 ou "site cloner"
6- logo em seguida é dado o ip da máquina permitindo que outras máquinas sejam acessadas por ela, enter
7- após isso é colocado a url do site que se deseja clonar, neste caso o facebook (http://www.facebook.com)
8- depois de dar enter e a url estar clonada, vamos acessar a mesma utilizando o ip da nossa máquina 
9- são mostradas no kali as informações a partir do momento que a página fake é usada 
