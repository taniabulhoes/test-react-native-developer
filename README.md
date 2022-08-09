# Teste para React Native Developer

> [![Tania Bulhoes Logo](https://images.squarespace-cdn.com/content/v1/625f0af3cbf96235f8de8b4a/539097a0-548d-4a84-a5fa-6cbbad1964a0/Tania_bulhoes_Logo_Horizontal_Positivo_RGB.png?format=1500w)](https://tbi.taniabulhoes.com.br/)
>
> Todos os interessados que fizerem Pull Request receberão um feedback da Tania Bulhões.<br>
> Essa prova consiste em testar seus conhecimentos em desenvolvimento de aplicações mobile cross-platform.
> Estamos priorizando desenvolvedores com conhecimento em React Native, portanto no momento não avaliaremos PRs em que o Dev entregue uma solução que não utilize React Native para desenvolvê-la.

### Requisitos
- React Native (https://facebook.github.io/react-native/)
- React (https://facebook.github.io/react/)
- Material Design (https://material.io/guidelines/)
- Native Components
- JSX
- Banco de dados NoSQL (MongoDB, Firebase, Realm, etc)

### Desejáveis
- Testes unitários

## Como participar?
> Basta fazer clone deste repositório e após finalizar a prova criar um Pull Request com o código do app para ser analisado por nós. :D
> No PR deixe qualquer diretiva necessária para rodar o projeto (Comandos para rodar a aplicação, testes, etc), bem como dependências (banco de dados, etc) localmente.

## Detalhes da prova
> A prova consiste em criar um app simples de To Do List (Lista de tarefas). <br>
> Sinta-se à vontade para utilizar quaisquer libs que desejar (Axios, Dio, etc). <br>
> Um build, resultando em uma apk (instalador) para Android deve ser gerado e a aplicação deverá rodar sem erros em um device real para fins de testes. <br>

### Funcionalidades
> Deve conter no app as seguintes funcionalidades:

1. Navegação com dados do usuário e itens de menu
1. Listagem de tarefas
2. Criação de nova tarefa
4. Edição e exclusão de tarefa
5. Exibir alerta de confirmaçao de exclusão
6. Exibir Toaster feedbacks para erros que acontecerem na aplicação

*Obs.: Não é obrigatório criar página de login, mas caso queira será considerado um diferencial* <br>
*Obs².: Não é obrigatório seguir fielmente as cores e icones do protótipo, mas é importante tentar seguir a mesma estrutura (etapas, fluxos e afins)*

### Especificações técnicas
> O app deve se comunicar com uma base de dados externa via REST API, para isso recomendamos a utilização do [Firebase](https://firebase.google.com). <br>
> As tarefas devem seguir a estrutura JSON abaixo

```
{
  title: String,
  description: String,
  date: DateTime,
  completed: Boolean,
  created_at: Date
  updated_at: Date
}
```

### Protótipo do app
> Click para ampliar as imagens <br>

[![Menu](http://i.imgur.com/U443Ore.jpg)](http://i.imgur.com/Zpj5lwj.png)
[![List](http://i.imgur.com/Eb88PkA.jpg)](http://i.imgur.com/0zihnYm.png)
[![Create](http://i.imgur.com/KacMBSo.jpg)](http://i.imgur.com/6Fb53k7.png)
[![Edit](http://i.imgur.com/Wf478tT.jpg)](http://i.imgur.com/gL8OMVF.png)

## Dúvidas?
> diego.vilarinho@taniabulhoes.com.br <br>
> Company Presentation: https://tbi.taniabulhoes.com.br/
> Ecommerce: https://www.taniabulhoes.com.br/

### Desde já agradecemos e boa sorte! ;)
