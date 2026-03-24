# lachaise-template-pandoc

Este projeto é um template para gerar PDFs a partir de arquivos Markdown utilizando o Pandoc.

## Como exportar para PDF

1. Certifique-se de que o [Pandoc](https://pandoc.org/) está instalado em seu sistema.

- **No Fedora**, você pode instalar com:

    ```sh
    sudo dnf install pandoc
    ```

- No Ubuntu/Debian, use:

    ```sh
    sudo apt-get install pandoc
    ```

- Ou consulte a [documentação oficial](https://pandoc.org/installing.html) para outros sistemas.

2. Para gerar o PDF, execute o seguinte comando no terminal, na raiz do projeto:

  ```sh
  pandoc main.md -o example.pdf
  ```

  Isso irá converter o arquivo `main.md` em um PDF chamado `example.pdf`.

## Estrutura do projeto

- `main.md`: Arquivo principal em Markdown.
- `structure.tex`: Arquivo de estrutura LaTeX opcional para customização.
- `README.md`: Este arquivo de instruções.

## Observações

- Certifique-se de ter o LaTeX instalado para que o Pandoc consiga gerar PDFs corretamente.
- Você pode customizar o template editando o arquivo `structure.tex`.
