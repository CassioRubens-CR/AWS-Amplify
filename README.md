# Creating Web Application Using AWS Amplify

## Criando um aplicativo web usando AWS Amplify

[AWS Amplify](https://aws.amazon.com/pt/amplify/) fornece um fluxo de trabalho CI/CD baseado em Git para criar, implantar e hospedar aplicações Web de página única ou sites estáticos com back-ends sem servidor. Ao conectar-se a um repositório Git, o Amplify determina automaticamente as configurações de compilação para a estrutura de trabalho do front-end e todos os recursos de back-end sem servidor configurados com a CLI do Amplify e implanta automaticamente atualizações a cada confirmação de código. ( [Fonte e instruções](https://aws.amazon.com/pt/getting-started/hands-on/build-react-app-amplify-graphql/module-one/) ).

___

### Instalação da CLI do Amplift

`CLI(Interface de Linhas de Comando)` do Amplify é um conjunto de ferramentas unificado para criar Serviços de Nuvem AWS para seu aplicativo seguindo um fluxo de trabalho simples e guiado, ou seja, permite criar, gerenciar e remover serviços da AWS diretamente do seu terminal. ( [Fonte e instruções](https://aws.amazon.com/pt/getting-started/hands-on/build-react-app-amplify-graphql/module-two/) ).

`Bibliotecas do Amplify` – As bibliotecas do Amplify permitem interagir com os serviços da AWS de uma aplicação móvel ou Web.

`Autenticação` – Em software, autenticação é o processo de verificação e gerenciamento da identidade de um usuário, usando um serviço de autenticação ou API. Usamos os componentes:

- `withAuthenticator` - Esse componente estruturará todo o fluxo de autenticação do usuário, permitindo que eles se cadastrem, façam login, redefinam senhas e confirmem o login para a autenticação multifator (MFA).

- `AmplifySignOut` - Que renderizará o botão Sign Out (Sair).

___

### Adicionado uma API GraphQL e um banco de dados

Criado uma API ao aplicativo usando as bibliotecas e a CLI do Amplify. A API é uma `GraphQL` que usa o `AWS AppSync`(um serviço GraphQL gerenciado), que tem o suporte do `Amazon DynamoDB`(um banco de dados NoSQL). ( [Fonte e instruções](https://aws.amazon.com/pt/getting-started/hands-on/build-react-app-amplify-graphql/module-four/) ).

___

### Adicionado Serviço de armazenamento

Criado um serviço de armazenamento usando o `Amazon S3`, com capacidade de associar uma imagem, utilizando a CLI e as bibliotecas do Amplify. Atualizando o `GraphQL` para associar uma imagem a cada nota, permitindo o upload, a busca e a renderização de imagens. ( [Fonte e instruções](https://aws.amazon.com/pt/getting-started/hands-on/build-react-app-amplify-graphql/module-five/?e=gs2020&p=build-a-react-app-four) ).

___

### Conclusão

Foi implementado uma aplicação Web usando o AWS Amplify!
Adicionado autenticação ao aplicativo, permitindo que os usuários se cadastrem, façam login e gerenciem suas contas.
O aplicativo também tem uma API GraphQL escalonável configurada com um banco de dados Amazon DynamoDB, permitindo aos usuários criar e excluir notas.
Foi adicionado ainda o armazenamento de arquivos usando o Amazon S3, permitindo que os usuários fazem upload e visualizem as imgens em seus aplicativos.

## 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- `JavaScript`
- [ReactJS](https://reactjs.org)
- [Git](https://git-scm.com)
- [ASW Amplify](https://aws.amazon.com/pt/amplify/)
- [AWS AppSync](https://aws.amazon.com/pt/appsync/)
- [Amazon DynamoDB](https://aws.amazon.com/pt/dynamodb/)
- [GraphQL](https://aws.amazon.com/pt/graphql/)
- [Amazon S3](https://aws.amazon.com/pt/s3/)

___

### :black_nib: Cássio Rubens 🚀

- [Portfólio](https://cassiorubens-cr.github.io/portfolio/)
- [GitHub](https://github.com/CassioRubens-CR)
- [Linkedin](https://www.linkedin.com/in/cássio-rubens)
