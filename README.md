#MARDEV

Configurando o vagrant para rodar essa infraestrutura

OBS para windows:

1- Você deve ter o suporte a virtualização habilitado em seu computador;
2- Seu Windows deve ser 64bits versão 1607 e build: 14393.0;
3- Você deve ter instalado o virtualbox;

DOWNLOADS

Virtualbox para windows: http://download.virtualbox.org/virtualbox/5.1.20/VirtualBox-5.1.20-114628-Win.exe

Virtualbox para Mac http://download.virtualbox.org/virtualbox/5.1.20/VirtualBox-5.1.20-114629-OSX.dmg

RODAR INFRAESTRUTURA:

1 - Clonar esse repositorio com o comando (pode copiar e colar):

git clone https://github.com/fabricamardev/appetcareVagrant.git

2 - Entrar no diretorio criado com o comando (Windows/Mac/linux):

cd appetcareVagrant

3 - De dentro do diretorio appetcareDocker iniciar o container com o comando:

vagrant up

Feito isso os serviços podem ser acessados nas seguintes portas:

    mysql na porta 3306;
    laravel na porta 8080 (http://localhost);
    PhpMyAdmin na porta 8080 diretorio phpmyadmin (http://localhost:8080/phpmyadmin) user: root e senha: vagrant

ESTRUTURA DE PASTAS:

    www : Arquivos do módulo web (copiar aqui os arquivos do projeto)
    
Reportar dúvidas e erros para fabricamardev@gmail.com
