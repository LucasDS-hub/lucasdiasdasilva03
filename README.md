# Teste de Login - SauceDemo
Este projeto contém um teste automatizado utilizando o Cypress para realizar o login no site SauceDemo.

# Descrição
O teste verifica se a funcionalidade de login no site SauceDemo funciona corretamente. Ele realiza a seguinte sequência de ações:
1. Acessa o site SauceDemo.
2. Preenche o campo de usuário com "standard_user" e o campo de senha com "secret_sauce".
3. Clica no botão de login.
4. Verifica se o usuário foi redirecionado para a página de inventário (com URL contendo "/inventory.html").
5. Verifica se o título "Products" está visível na página de inventário.

# Pré-requisitos
Ter o Cypress instalado no seu projeto.
