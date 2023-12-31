# Propagule
 Page to generate equivalence seed bitcoin in numbers BIP0039
# Instruções de Uso

Este código em PHP foi desenvolvido para ajudar na recuperação de palavras sementes de carteiras Bitcoin. Ele permite que você digite as palavras sementes e obtenha a lista de números correspondentes. Em seguida, você pode digitar esses números para obter as palavras sementes na ordem correta.

## Pré-requisitos

- PHP instalado em seu ambiente de desenvolvimento local.
- Servidor web local (por exemplo, XAMPP, WAMP, ou MAMP).

## Passos

1. Faça o clone deste repositório em sua máquina local ou baixe o arquivo ZIP.
2. Configure o servidor web local para apontar para a pasta onde o código foi baixado.
3. Certifique-se de que a extensão `zip` esteja habilitada no arquivo `php.ini`.
4. Certifique-se de que a pasta onde o código está localizado tenha permissões de gravação.
5. Abra o navegador da web e acesse o endereço do servidor local.
6. Digite as palavras sementes de sua carteira Bitcoin no campo de texto, separadas por vírgulas.
7. Clique no botão "Enviar" para obter a lista de números correspondentes às palavras sementes.
8. Os números serão exibidos na página em uma fonte grande.
9. Para obter as palavras sementes na ordem correta, digite os números separados por vírgulas no campo de texto.
10. Clique no botão "Enviar" para obter as palavras sementes correspondentes aos números digitados.
11. As palavras sementes serão exibidas na página em uma fonte grande.

**Importante**: Certifique-se de executar este código localmente, sem conexão com a internet. Isso é crucial para garantir a segurança de suas palavras sementes e evitar qualquer risco relacionado à exposição de informações pessoais em um ambiente online.

## Aviso

Este código foi projetado para ser executado localmente em um ambiente de desenvolvimento controlado. Não é recomendado executá-lo em um servidor web público ou em um ambiente de produção sem tomar as devidas precauções de segurança.

## Tails
Para executar o servidor Apache no Tails e abrir um arquivo em PHP, siga estas etapas:

Inicie o Tails e aguarde até que esteja totalmente inicializado.

Abra o Terminal. Você pode fazer isso clicando com o botão direito na área de trabalho e selecionando "Abrir Terminal" no menu de contexto.

Digite o seguinte comando para iniciar o servidor Apache:

sudo service apache2 start
Pressione Enter e digite a senha do usuário root (geralmente "amnesia") quando solicitado. O servidor Apache será iniciado.

Agora, coloque o arquivo PHP que você deseja executar no diretório padrão do Apache. O diretório padrão é /var/www/html/.

Por exemplo, se você tiver um arquivo chamado "exemplo.php", copie-o para o diretório /var/www/html/. Você pode usar o comando cp para fazer isso. Por exemplo:

sudo cp caminho/do/arquivo/exemplo.php /var/www/html/
Abra um navegador da web no Tails e digite o seguinte endereço na barra de URL:

http://localhost/propagule.php
O arquivo PHP será executado e você poderá ver a saída no navegador.

Certifique-se de que o Tails esteja configurado corretamente e tenha as permissões necessárias para executar o servidor Apache. Tenha em mente que o Tails é projetado para fornecer um ambiente de navegação seguro e anônimo, e a execução de um servidor web pode ter implicações de segurança e privacidade. Certifique-se de entender os riscos associados antes de prosseguir.

