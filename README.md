
# Insta Gift

Link de documentação atualizada: https://chief-hydrangea-97a.notion.site/Insta-Gift-57f07658b7074b0bb6995bcce194a7a7

## O Problema
Presentear é um ato que vai além do materialismo, sendo uma maneira de expressar sentimentos, apreciação e conexões emocionais. No entanto, encontrar o presente ideal muitas vezes é uma jornada cheia de incertezas. As preferências individuais estão constantemente mudando e podem ser influenciadas por inúmeras variáveis, como hobbies, interesses, histórico de compras e até mesmo as **interações nas redes sociais**.

## Objetivo
A aplicação tem como objetivo gerar uma recomendação de presente para um indivíduo com base nas fotos publicadas em seu perfil no Instagram.

## Solução Proposta
A aplicação tem como objetivo simplificar e aprimorar a experiência de escolha de presentes. Ela irá coletar dados públicos disponíveis no perfil do Instagram para compreender melhor a personalidade e os gostos da pessoa em questão. Ao analisar estes dados, a aplicação será capaz de identificar itens específicos disponíveis no nosso catálogo de produtos que podem ser de interesse da pessoa.

## Roadmap do Projeto
O roadmap do projeto está detalhado [aqui](https://github.com/users/Gabukuro/projects/3/views/3).

## Diagramas
A seguir a lista de diagramas da aplicação:
- [Diagrama de Casos de Uso](./assets/user%20cases%20diagram.drawio.png)
- [Diagrama de Sequência](./assets/sequence%20diagram.drawio.png) (Desatualizado)
- [Diagrama de Sequência](./assets/insta-gift%20sequence%20diagram-Page-5.drawio.png) (Atualizado)
- [Diagrama de Sequência Pooling do Frontend](./assets/insta-gift%20sequence%20diagram-Page-4.drawio.png) 
- [Modelagem de Dados](./assets/data%20model%20diagram.drawio.png) (Desatualizado)
- [Modelagem de Dados](./assets/insta-gift%20sequence%20diagram-data%20model%20diagram.drawio%20(1).png) (Atualizado)

## Diretórios do Projeto

### Repositórios Relacionados
- [API da Aplicação](https://github.com/Gabukuro/insta-gift-api)  - [Link do API (Produção)](http://3.128.213.201:8000/status)
- [Frontend em Vue.js da Aplicação](https://github.com/Gabukuro/insta-gift-app) - [Link do Vercel (Produção)](https://insta-gift-app.vercel.app/)
- [Localstack para Desenvolvimento Local](https://github.com/Gabukuro/insta-gift-localstack)
- [Object Detection Service](https://github.com/Gabukuro/object-detection-service)

- [Link do Sonar (Produção)](http://3.140.235.13:9000/)
- [Link do Betterstack](https://uptime.betterstack.com/team/179873/monitors/1588685)

### Observações
Como a api não possui certificado ssl é possível que ao abrir a aplicação no vercel você tenha problemas ao realizar as requisições para o servidor. Para contornar este problema é preciso habilitar `Insecure Content` nas configurações do site:
1. Clique nas configurações do site: <br>
   ![image](https://github.com/Gabukuro/insta-gift/assets/48013350/d10afba5-6f03-47de-989e-2d79bff0a78e)

3. Em seguida vai aparecer uma lista com vária pesmissões, encontre a opção `Insecure Content` e selecione permitir:<br>
   ![image](https://github.com/Gabukuro/insta-gift/assets/48013350/b5b3c8ea-d854-4389-bca7-cd2b69114a20)

Feito isso, agora a aplicação pode acessar a api.
