# Sistema de Gestão de Clientes

Este é um sistema simples de gestão de clientes que permite cadastrar informações em uma planilha do Excel. A interface gráfica foi desenvolvida utilizando a biblioteca `customtkinter`, que oferece um visual moderno e customizável.

## Funcionalidades

- Interface gráfica amigável e moderna.
- Cadastro de clientes com campos para Nome, Telefone, Idade, Gênero, Endereço e Observações.
- Salva os dados cadastrados em uma planilha do Excel (`Clientes.xlsx`).
- Limpa automaticamente os campos do formulário após o envio dos dados.

## Requisitos

Para executar este projeto, você precisa ter Python 3 instalado e as seguintes bibliotecas:

- `customtkinter`: Biblioteca para criação de interfaces gráficas modernas.
- `openpyxl`: Biblioteca para manipulação de arquivos Excel.
- `tkinter`: Biblioteca padrão do Python para interfaces gráficas.

## Instalação

1. Clone este repositório:
    ```sh
    git clone https://github.com/seu-usuario/sistema-gestao-clientes.git
    ```

2. Navegue até o diretório do projeto:
    ```sh
    cd sistema-gestao-clientes
    ```

3. Crie um ambiente virtual (opcional, mas recomendado):
    ```sh
    python -m venv venv
    source venv/bin/activate  # No Windows, use `venv\Scripts\activate`
    ```

4. Instale as dependências:
    ```sh
    pip install customtkinter openpyxl
    ```

## Como usar

1. Execute o script principal:
    ```sh
    python app.py
    ```

2. Preencha os campos do formulário e clique em "SALVAR DADOS" para cadastrar um novo cliente. Os dados serão salvos na planilha `Clientes.xlsx`.

3. Após o envio dos dados, os campos do formulário serão limpos automaticamente para permitir novos cadastros.

## Estrutura do Projeto

- `app.py`: Script principal que contém o código do sistema de gestão de clientes.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.



