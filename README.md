
# RegisterUserEmail

Este é um projeto desenvolvido em Laravel 10 para fornecer funcionalidades de registro de usuário e envio de email de boas-vindas após o registro.

## Funcionalidades

- Controle e Rotas da API: Implementamos controle e rotas na camada API do Laravel para manipular o registro de usuários.
- Eventos e Listeners Personalizados: Utilizamos eventos e ouvintes personalizados para acionar o envio de email de boas-vindas após o registro bem-sucedido do usuário.
- Envio de Email com Laravel: Configuramos o envio de email utilizando as funcionalidades embutidas do Laravel, garantindo um processo simples e eficaz.
- Utilização de Fila para Envio de Email: Para melhorar o desempenho e a escalabilidade, implementamos o envio de email em fila, garantindo um processamento assíncrono e eficiente.

## Requisitos

Certifique-se de ter o ambiente Laravel configurado e as dependências instaladas antes de executar o projeto.

## Configuração

- Clone o repositório para o seu ambiente local.
- Execute composer install para instalar as dependências do Laravel.
- Configure o arquivo .env com as informações necessárias, incluindo as credenciais do servidor de email.
- Execute php artisan migrate para criar as tabelas do banco de dados necessárias.
- Execute php artisan serve para iniciar o servidor Laravel.

## Uso
Você pode acessar as rotas da API para registrar um novo usuário e automaticamente enviar um email de boas-vindas. Certifique-se de seguir a documentação da API para detalhes sobre as requisições necessárias.

## Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue para relatar problemas ou propor novas funcionalidades.

## Licença
Este projeto está licenciado sob a Licença MIT.
