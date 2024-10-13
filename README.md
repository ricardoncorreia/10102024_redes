# 10102024_redes
descrição do execicio - Criação de um dominio, de máquinas, de sites e a sua configuração

1ºpasso:
  - Criação das maquinas ( 1 server, 3 clientes )
![{E2256DFC-0A96-41C6-953F-3F5A1F5DA39C}](https://github.com/user-attachments/assets/dcf4d834-4bd9-4a1a-b828-7843599d2b15)

  - Adição das 4 máquinas à mesma vpc, virtual private cloud, com IP 10.0.0.0/20 e à mesma subnet 10.0.0.0/24, respetivamente.
![{F734ED2A-4781-4BBC-8621-56C038652F81}](https://github.com/user-attachments/assets/9d91a219-43bb-4202-9df2-a4cd53897d47)
![{F86830F6-F9F7-479D-AFD9-C2FA9CFC2FA5}](https://github.com/user-attachments/assets/c99c66a5-863c-42fb-b9b8-0acae12fa7c5)

  - Adição do mesmo securitygroup para as 4 máquinas (default) permitindo a entrada dos protocolos: ssh (port 22), ftp (port 21), http (ports 80, 8080, 8088), https (port 443) 
![{030B0621-5ACC-4C75-A7ED-C92EAB2AEBD9}](https://github.com/user-attachments/assets/b11e0a9f-c9ab-42bf-8eab-7729662b6861)

  - adição da KeyPair para acesso, através da conta de administrador do aws (Keyname == windows)
![{8D436AA8-5B48-44B0-AC6B-413216E43CB3}](https://github.com/user-attachments/assets/643b1b07-03af-4728-a43d-bcfe4f8605ee)

  - Atribuição de IPs públicos às maquinas para acesso à Internet.
![{8606CC84-D357-45D9-9645-12E03CFDE7B5}](https://github.com/user-attachments/assets/e3d11270-8573-427d-b16b-bad28750525e)
    



2ºpasso:
  - Criação do AD
  - Configuração do Domain Controller ( server ) 
  - Configuração do DNS
  - Criação dos utilizadores
  - Adição dos 3 clientes ao dominio "enta.pt"
  - Criação dos websites

3ºpasso:
  - Permissões efetuadas para o acesso aos sites
  - roaming das contas dos utilizadores

4ºpasso:
  - Instalação do Filezilla Server na máquina servidor
  - Instalação do Filezilla Cliente nas máquinas clientes
  - Desativação das firewalls nas máquinas clientes e servidores
  - Ativação de portas na security rules para permitir a aplicação filezilla
