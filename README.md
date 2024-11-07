### Inicalização

- Abra o VS Code
- Clone este repositório do github 
- Abra o terminal do VS Code e rode os seguintes comando:

```
npm i
npm run dev
```

- Abra o navegador e abra o site `http://localhost:3000`

### Testando

- Para testar a permissão da criação de usuários, pressione o botão Cadastrar e preencha o formulário
- Você receberá uma mensagem de erro e será enviado de volta para a página de login
- Preencha o formulário de login com as seguintes informações:

```
Email: jorge@mail.com
Senha: quemejorge
```

- Você receberá uma mensagem de sucesso e será enviado novamente até a página de registro, onde deverá preencher o formulário
- Por estar logado, você receberá uma mensagem de sucesso e não será enviado de volta para a página de login
- Você poderá voltar para a página de login pressionando o botão cancelar
- Na página de login você poderá preencher o formulário, assim testando se os usuários foram inseridos corretamente 
