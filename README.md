README — Instagram
1. Sobre o projeto
O projeto Instagram é um aplicativo desenvolvido utilizando Flutter e Dart, com o objetivo de simular uma rede social. O aplicativo apresenta um feed de publicações com imagens relacionadas ao Corinthians, permitindo que o usuário interaja com as postagens por meio de botões de curtida, comentário e compartilhamento.
2. Objetivo
O objetivo do projeto é colocar em prática os conhecimentos adquiridos no desenvolvimento de aplicativos, utilizando componentes visuais, imagens, listas e interações com o usuário.
3. Tecnologias utilizadas
- Flutter: framework utilizado para desenvolver a interface do aplicativo.
- Dart: linguagem de programação utilizada para escrever o código.
- Material Design: padrão visual utilizado na construção dos componentes da interface.
4. Funcionalidades
O aplicativo possui um feed que apresenta publicações com imagens e identificação do usuário. Cada publicação possui botões de interação.

A funcionalidade de curtida permite que o usuário curta e descurta uma publicação, atualizando o ícone de coração e a quantidade de curtidas exibida na tela.

Os botões de comentário e compartilhamento apresentam mensagens para indicar que foram acionados. Entretanto, essas funções ainda não possuem integração com um sistema real de comentários ou compartilhamento.
5. Estrutura do projeto
O projeto está organizado em pastas que separam o código principal, as imagens e os arquivos de configuração.
- lib/main.dart: contém o código principal e a implementação da tela do feed.
- imagens: armazena as imagens utilizadas nas publicações.
- test: contém os arquivos relacionados aos testes do aplicativo.
- pubspec.yaml: arquivo responsável pelas configurações do projeto e pela declaração dos recursos utilizados.
6. Como executar o projeto
Para executar o aplicativo, é necessário ter o Flutter instalado e configurado no computador.

Primeiramente, extraia os arquivos do projeto e abra a pasta no Visual Studio Code ou em outra IDE compatível. Em seguida, abra o terminal e execute o comando flutter pub get para instalar as dependências.

Após a instalação, execute flutter run para iniciar o aplicativo em um dispositivo ou emulador compatível.
7. Funcionamento do aplicativo
O aplicativo utiliza componentes do Flutter para organizar as publicações em uma lista. As imagens são exibidas no feed, enquanto os botões permitem interações com a interface.

O recurso setState() é utilizado para atualizar a tela quando o usuário curte ou descurte uma publicação. Dessa forma, o ícone e o contador de curtidas são modificados de acordo com a interação realizada.

As imagens armazenadas localmente devem ser carregadas com o recurso Image.asset(), com os caminhos devidamente configurados no arquivo pubspec.yaml.
8. Limitações
Atualmente, o aplicativo possui funcionalidades básicas. As curtidas não são salvas permanentemente, e os botões de comentário e compartilhamento apenas demonstram uma interação visual. O projeto também não possui sistema de login, banco de dados ou integração com servidores externos.
9. Melhorias futuras
Como melhorias futuras, podem ser implementados um sistema de cadastro e login, a criação de novas publicações, comentários reais, compartilhamento de conteúdo e armazenamento permanente das informações em um banco de dados.
10. Conclusão
O projeto permite aplicar conceitos fundamentais do desenvolvimento de aplicativos com Flutter e Dart, incluindo construção de interfaces, organização de listas, utilização de imagens e gerenciamento de estados. Além disso, serve como base para o desenvolvimento de uma aplicação mais completa, com funcionalidades semelhantes às de uma rede social.
