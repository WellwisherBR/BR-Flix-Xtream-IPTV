# BR-Flix (Xtream IPTV)

Apenas um projeto desenvolvido para os estudos, espero que gostem :D

Características:
  - Perfil próprio
  - Assistidos recentemente
  - Lista de favoritos
  - Ponto de verificação (Salva seu tempo de jogo)
  - Próximo episódio automático (Avança para o próximo episódio quando o vídeo atinge 99%)
  - Marcação de episódios já assistidos (Episódios já assistidos são marcados em verde)
  - Barra de pesquisa
  - Navegue por filmes e séries por categoria
  - Multilíngue (Atualmente português/inglês, você pode adicionar uma tradução para todo o site modificando apenas algumas linhas)
  - Atualizar a lista (Disponível apenas para usuários com nível 10)

Requisitos:
  - Composer (`composer install`)
  - Servidor web com reescrita de URLs
  - PHP 7.4 ou maior (8.1 recomendado)
  - Lista IPTV com suporte à API Xtream

Instalação:
  - Instalar o XAMPP 8.1
  - Instalar o Composer (`https://getcomposer.org`)
  - Colar os arquivos na pasta `htdocs`
  - Rodar o movies.sql da pasta `src`
  - abrir o cmd na pasta `htdocs` e usar o comando (`composer install`)
  - configurar seu banco de dados no arquivo `src/db.php`

Informação:
  - O pacote slimphp/Slim foi usado para controle de rotas e renderização. Certifique-se de instalá-lo corretamente.
  - Um usuário padrão será criado no banco de dados: usuário: admin senha: 123 (Este usuário já possui nível 10).
  - Certifique-se de configurar seu banco de dados no arquivo `src/db.php`
  - Permissão de escrita para a pasta e todos os seus arquivos.: `src/storage`

![Logo](./preview.png)
![Logo](./preview2.png)
![Logo](./preview3.png)
![Logo](./preview4.png)

