# Projeto de Cadastro de Usuários com Kivy e Python

Este é um projeto desenvolvido para praticar o uso do Kivy e Python. O objetivo principal é criar uma aplicação simples de cadastro e login de usuários utilizando uma interface gráfica.

## Estrutura do Projeto

O projeto é composto por dois arquivos principais:

- **`main.py`**: O script principal que gerencia a aplicação Kivy.
- **`database.py`**: A classe `DataBase` que lida com o armazenamento e manipulação de dados dos usuários.

## Funcionalidades

- **Cadastro de Usuário**: Permite criar uma nova conta com e-mail, nome e senha.
- **Login**: Permite que um usuário existente faça login com seu e-mail e senha.
- **Visualização de Conta**: Mostra informações sobre a conta do usuário logado, incluindo o nome, e-mail e data de criação.

## Dependências

Certifique-se de ter o Kivy instalado. Você pode instalá-lo usando pip:

```bash
pip install kivy
```

## Instruções de Uso

1. **Clone o Repositório**

   ```bash
   git clone <URL_DO_REPOSITÓRIO>
   cd <NOME_DO_REPOSITÓRIO>
   ```

2. **Crie a Pasta 'ui'**

   É necessário criar uma pasta chamada `ui` que contém o arquivo `my.kv`. Este arquivo é usado para definir a interface gráfica da aplicação. Você pode encontrar um exemplo básico deste arquivo no repositório.

3. **Execute a Aplicação**

   Para iniciar a aplicação, execute o seguinte comando:

   ```bash
   python main.py
   ```

## Estrutura do Código

- **`database.py`**: Define a classe `DataBase` responsável pela manipulação dos dados dos usuários.
- **`main.py`**: Define a interface e a lógica da aplicação Kivy, incluindo as classes de tela (`LoginWindow`, `CreateAccountWindow`, `MainWindow`) e o gerenciador de telas (`WindowManager`).

## Observações

- Certifique-se de que o arquivo `users.txt` exista no mesmo diretório que `main.py` para que o banco de dados funcione corretamente. Este arquivo será criado automaticamente na primeira execução do aplicativo.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests para melhorias e correções.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

Se precisar de mais alguma coisa ou de ajustes, é só me avisar!
![Captura de Tela (874)](https://github.com/Jonatasdotdev/Tela-de-login-kivy/assets/113778501/f2c22ee0-5a86-463f-9541-03f105a9ee81)
![Captura de Tela (873)](https://github.com/Jonatasdotdev/Tela-de-login-kivy/assets/113778501/685acc30-8eaa-4a6f-a742-6e15b9ff7c7a)

