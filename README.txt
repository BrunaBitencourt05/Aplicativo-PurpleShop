# 🛒 Mini Sistema de Lista de Compras em Python

Um mini sistema de gerenciamento de lista de compras interativo desenvolvido em Python. O projeto permite adicionar, visualizar, marcar como comprado e remover itens da lista de forma simples via terminal, mantendo os dados salvos em um arquivo CSV (**persistência de dados**).

---

## 📌 Funcionalidades

* ➕ **Adicionar itens:** Adiciona novos produtos à sua lista de compras.
* 👁️ **Visualizar lista:** Exibe todos os itens cadastrados com status visual de pendente `[ ]` ou concluído `[✓]`.
* M **Marcar como comprado:** Altera o status do item na lista para comprado.
* 🗑️ **Remover itens:** Exclui um item da lista pelo número de índice.
* 💾 **Persistência em CSV:** Todas as alterações são salvas e carregadas automaticamente no arquivo `lista_compras.csv`.

---

## 🛠️ Tecnologias Utilizadas

* **Python 3** (Lógica principal do sistema)
* **Biblioteca `csv`** (Nativa do Python, usada para salvar e carregar os dados)
* **Pandas** (Usada para análise e visualização rápida dos dados no ambiente de desenvolvimento)

---

## 🚀 Como Executar o Projeto

### Pré-requisitos
* Python 3 instalado ou acesso ao [Google Colab](https://colab.research.google.com/).
* Arquivo `lista_compras.csv` no mesmo diretório ou na pasta `/content/` no Colab.

### Passo a passo
1. Clone este repositório:
   ```bash
   git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)
