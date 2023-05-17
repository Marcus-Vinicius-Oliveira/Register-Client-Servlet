# Projeto de Cadastro e Listagem de Clientes - Página Web

Este projeto consiste em criar uma página web com formulário de cadastro e uma tela para listar os clientes já cadastrados. No formulário de cadastro, o usuário poderá informar o nome e CPF do cliente. Após o preenchimento, haverá um botão para executar a ação de cadastro, que chamará um servlet responsável pelo processamento. O servlet não precisa realizar validações, mas deve armazenar na sessão do usuário o cliente que foi cadastrado.

## Funcionalidades

O projeto oferece as seguintes funcionalidades:

- Página de Cadastro: exibe um formulário para que o usuário informe o nome e CPF do cliente a ser cadastrado.
- Ação de Cadastro: ao clicar no botão "Cadastrar", o servlet será acionado para processar o formulário e armazenar o cliente na sessão do usuário.
- Página de Listagem: possui um botão/link para acessar a listagem de todos os clientes cadastrados na sessão do usuário.

## Tecnologias Utilizadas

O projeto faz uso das seguintes tecnologias:

- **Java Servlet**: um componente Java que estende as capacidades de um servidor, permitindo o processamento de requisições e respostas HTTP.
- **HTML**: uma linguagem de marcação para estruturar e exibir o conteúdo na web.
- **CSS**: uma linguagem de estilo que define a aparência dos elementos HTML.
- **JavaScript**: uma linguagem de programação que adiciona interatividade e comportamento à página web.

## Configuração e Execução

Siga as etapas abaixo para configurar e executar o projeto localmente:

1. Clone o repositório do projeto:

```
git clone https://github.com/seu-usuario/nome-do-repositorio.git
```

2. Navegue até o diretório raiz do projeto:

```
cd nome-do-repositorio
```

3. Execute o projeto utilizando um servidor web, como o Apache Tomcat.

4. Acesse a página de cadastro em seu navegador através da URL: `http://localhost:8080/cadastro.html`

## Contribuição

Contribuições são bem-vindas! Se você encontrar algum problema ou tiver sugestões para melhorias, fique à vontade para abrir uma "issue" ou enviar um "pull request" no repositório do projeto.

## Licença

Este projeto está licenciado sob a [MIT License](https://opensource.org/licenses/MIT). Sinta-se à vontade para utilizar, modificar e distribuir o código-fonte conforme necessário.
