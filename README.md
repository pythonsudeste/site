# Site `sudeste.python.org.br`

Site base da Python Sudeste, que apenas fica responsável por fazer o redirecionamento de `sudeste.python.org.br` para `<ano atual>.sudeste.python.org.br`

Para configurar o redirecionamento, basta alterar o arquivo `index.html`. Exemplo:

```diff
<!DOCTYPE html>
<meta charset="utf-8">
<title>Redirecting to current website</title>
- <meta http-equiv="refresh" content="0; URL=https://2025.sudeste.python.org.br">
+ <meta http-equiv="refresh" content="0; URL=https://2026.sudeste.python.org.br">
- <link rel="canonical" href="https://2025.sudeste.python.org.br">
+ <link rel="canonical" href="https://2026.sudeste.python.org.br">
```

Se está organizando uma Python Sudeste e ainda não configurou o novo sub-domínio para o ano atual, crie uma [solicitação para a APYB](https://github.com/apyb/comunidade/discussions/) ([exemplo de 2025](https://github.com/apyb/comunidade/discussions/191)). Você vai precisar criar um novo repositório para a página do GitHub pages ([exemplo de 2025](https://github.com/pythonsudeste/pyse2025)), alterando o domínio e ativando o HTTPS nas configurações. 
