# Remote Authentication Use Case

> ## Caso de sucesso
1. Sistema valida os dados
2. Sistem faz uma requisição para a URL da api de login
3. Sistema valida os dados recebidos da api
4. Sistema entrega os dados da conta do usuário

> ## Exceção - URL inválida
1. Sistema retorna uma mensagem de erro inesperado

> ## Exceção - Dados inválidos
1. Sistema retorna mensagem de dados inválidos

> ## Exceção - Resposta inválida
1. Sistema retorna mensagem de erro inesperado

> ## Exceção - Falha no servidor
1. Sistema retorna mensagem de erro inesperado

> ## Exceção - Credenciais inválidas
1. Sistema retorna mensagem de erro informando que as credenciais estão erradas
