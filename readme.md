# Notebooks da Disciplina

Repositório destinado ao armazenamento dos **notebooks Jupyter utilizados nas aulas práticas da disciplina**.

Os notebooks contêm exemplos, exercícios e atividades práticas desenvolvidas ao longo das aulas, permitindo que os alunos acompanhem e executem os códigos apresentados durante a disciplina.

---

## Objetivo

O objetivo deste repositório é centralizar os materiais práticos da disciplina em um único local, facilitando o acesso e a gestão dos recursos utilizados nas aulas práticas.

## Tecnologias e ferramentas

Os notebooks podem utilizar diferentes tecnologias e bibliotecas de acordo com o conteúdo de cada aula.

### Principal
- Python
- Jupyter Notebook


## Bibliotecas

As bibliotecas utilizadas serão apresentadas e instaladas conforme a necessidade de cada notebook.

### Alguns exemplos:

- pandas
- numpy
- matplotlib
- scikit-learn
- nltk

## Como executar os notebooks

### Opção 1 - Google Colab

A forma mais simples de executar os notebooks é utilizando o Google Colab.

- Acesse o notebook desejado.
- Faça o download do arquivo .ipynb.
- Abra o Google Colab.
- Selecione Arquivo → Fazer upload de notebook.
- Selecione o notebook baixado.
- Execute as células utilizando o botão ▶️.

O Google Colab permite executar Python diretamente no navegador, sem a necessidade de instalar o ambiente localmente.

Aqui está o Markdown corrigido e formatado para colar diretamente no seu `README.md`.

A numeração dos itens foi ajustada (faltava o item 2 e o item 3 estava desalinhado), os blocos de código foram configurados corretamente e os atalhos foram destacados para melhor leitura no GitHub.


### Opção 2 - Visual Studio Code

Também é possível executar os notebooks diretamente pelo **Visual Studio Code (VS Code)**.

#### 1. Instalar o Python

Certifique-se de que o **Python** esteja instalado no computador. Para verificar a instalação, abra o terminal e execute:

```bash
python --version

```

#### 2. Instalar as extensões

No VS Code, acesse a área de extensões (`Ctrl + Shift + X` ou `Cmd + Shift + X` no macOS) e instale:

* **Python** (Microsoft)
* **Jupyter** (Microsoft)

Essas extensões permitem executar e visualizar arquivos `.ipynb` diretamente no VS Code.

#### 3. Instalar as dependências

Abra o terminal integrado do VS Code:

* Menu superior: **Terminal** → **New Terminal**
* Ou utilize o atalho: `Ctrl + ``

Em seguida, instale as dependências do projeto:

```bash
pip install -r requirements.txt

```

Caso o repositório não possua um arquivo `requirements.txt`, instale as bibliotecas utilizadas na atividade. Por exemplo:

```bash
pip install pandas numpy matplotlib scikit-learn

```

#### 4. Abrir o notebook

No explorador de arquivos do VS Code, navegue até a pasta da aula e abra o arquivo `.ipynb`:

```text
aula-01/
└── aula_01.ipynb

```

O VS Code exibirá o notebook diretamente no editor.

#### 5. Selecionar o interpretador Python

No canto superior direito do notebook, clique em **Select Kernel** e escolha a versão do Python que será utilizada para executar as células (por exemplo, `Python 3.12.x`).

> **Importante:** O interpretador selecionado deve ser o mesmo no qual você instalou as bibliotecas no passo anterior.

#### 6. Executar o notebook

* Cada célula possui um botão **▶ Run Cell** ao lado. Clique nele para executar uma célula individualmente.
* Para rodar o código inteiro de uma vez, utilize a opção **Run All** no menu superior do notebook.

O resultado da execução será apresentado diretamente abaixo de cada célula.


## Licença

Este repositório é destinado ao uso acadêmico e educacional.

Os materiais devem ser utilizados respeitando as orientações fornecidas pelo professor e as políticas institucionais aplicáveis.