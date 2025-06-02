# pandas-file-io-solutions

Manipulating data from multiple sources (CSV, XLSX, Google Sheets, JSON, HTML, XML, and SQLite) using Python, the Pandas library, and the Jupyter Notebook environment.

## Estrutura do Projeto

Este projeto está organizado da seguinte forma para facilitar a navegação e o desenvolvimento:

* `data/`: Contém todos os arquivos de dados brutos e processados utilizados ou gerados pelo projeto (CSV, JSON, Excel, etc.).
* `notebooks/`: Aqui você encontrará os Jupyter Notebooks com exemplos de manipulação de dados, análises exploratórias e demonstrações de funcionalidades.
* `README.md`: Este arquivo, que oferece uma visão geral e documentação do projeto.
* `requirements.txt`: Lista todas as bibliotecas Python necessárias para rodar o projeto.

---

## Como Usar

Para começar com este projeto:

1. Clone este repositório;
2. Execute os comandos abaixo:
```
python3 -m venv venv

source venv/bin/activate  # Unix/macOS
# ou
venv\Scripts\activate  # Windows

pip install -r requirements.txt

python3 -m ipykernel install --user --name=pandas-file-io-solutions_venv

```
3. Explore os notebooks na pasta `notebooks/` para ver exemplos de como manipular os dados.
4. Após abrir um arquivo do Jupyter Notebook, selecione o Kernel pandas-file-io-solutions_venv;
