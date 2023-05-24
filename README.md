# BACKEND Do App ProPlayers_CSGO

## Sobre

Trabalho destinado a evolução da aplicação mobile da disciplina de Programação de dispositivos móveis no semestre de 2023.1, consistindo na criação de aplicações BACK-END  para servir a parte FRONT-END. Conforme as instrução dessa avaliação, a aplicação foi dividida em dois microserviços, ambos construidos utilizando as mesmas ferramentas - Framework NestJS, ORM Prisma e Banco de Dados Sqlite :
1 - **players** - Consistem uma aplicação com apenas uma rota que recebe uma requisição do tipo get e retorna todos os Jogadores cadastrados no banco de dados. Esse serviço é consumido nos Componentes Feed e Search da aplicação FRONTEND.
2 - **favorites** - Esse serviço é responsável por salvar, exibir e excluir dados dos jogadores favoritos do usuário e para isso dispõe de três rodas distintas para executar essas interações com o seu próprio banco de dados. Ele é consumido no Componetne Feed da apllicação, quando o usuário seleciona um jogador que deseja inserir na sua coleção de favoritos e no Componente Favorites, para mostrar todos os jogadores salvos na coleção e para remover um jogador ao clicar no botão.
...

# Instruções de uso
Para execução dos containers, é necessário que o usuário tenha instalado em sua máquina o docker e docker compose.
0 **Players:**
1 - Navegar até a pasta da aplicação - cd players-service
2 - Executar o comando docker compose up
