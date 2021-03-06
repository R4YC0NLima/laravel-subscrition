# Teste Laravel Pleno
O teste é um CRUD de lojas com vários produtos

<table style="width:100%">
    <thead>
      <tr>
        <th></th>
        <th>Ambiente de trabalho</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><img src="https://www.docker.com/sites/default/files/d8/2019-07/Moby-logo.png" width="50" alt="docker"></td>
        <td>Docker</td>
        <td><a target="_blank" href="https://www.docker.com/">https://www.docker.com/</a></td>
      </tr>   
      <tr>
        <td><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Laravel.svg/1200px-Laravel.svg.png" width="50" alt="laravel"></td>
        <td>Laravel 8</td>
        <td><a target="_blank" href="https://laravel.com/">https://laravel.com/</a></td>
      </tr> 
      <tr>
        <td><img src="https://seeklogo.com/images/I/insomnia-logo-A35E09EB19-seeklogo.com.png" width="50" alt="insomnia"></td>
        <td>Insomnia</td>
        <td><a target="_blank" href="https://insomnia.rest/">https://insomnia.rest/</a></td>
      </tr>    
    </tbody>
</table>

## Características da aplicação
<!-- * [] - Testes unitários e de integração -->
* [x] - Aunteticação
* [x] - Construção de frontend
* [x] - Intalação e configuração do Laravel Cashier
* [x] - CRUD Assinatura
* [x] - Configurar Checkout do stripe
* [x] - Gerar token de cartão do stripe
* [x] - Verificar se o Usuário é assinante e depois o middleware dele
* [x] - Exibir faturas do stripe com o Laravel
* [x] - Cancelar e reativar assinatura Laravel Cashier
* [x] - Home do site
* [x] - Planos de forma dinâmica
* [x] - Escolher planos para assinar o Laravel Cashier
* [x] - Configurar o Vue.js no Laravel / Criar Components
* [x] - Criar API para enviar E-mails e depois Enviar email com o Vue.js e Laravel
* [x] - Envio de email de contato em fila
* [x] - Adicionar Preloader e validação de checkout
* [x] - Exibir detalhes da assinatura do stripe
* [x] - Webhooks Stripe


<!-- * [] - Worflow adicionado; -->

## Comandos de execução

- Para iniciar o projeto pela primeira vez, execute:
```
    docker-compose up -d --build
```
- Após o 1º build, poderá está executando sem a flag --build
```
    docker-compose up -d
```
- Para derrubar os container, execute:
```
    docker-compose down
```