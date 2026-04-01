# Módulo 24 – Bancos de Dados + SQL

**Este notebook apresenta uma atividade prática de introdução ao uso de SQL com SQLite integrado ao Python, utilizando uma base de dados de vendas.**

## Tecnologias Utilizadas

| Tecnologia | Versão | Propósito |
|-----------|--------|----------|
| ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) | 3.7+ | Linguagem principal |
| ![SQLite](https://img.shields.io/badge/SQLite-07405E?logo=sqlite&logoColor=white) | 3.x | Banco de dados |
| ![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white) | Latest | Manipulação de dados |


### Objetivo

**Explorar conceitos fundamentais de consultas SQL aplicadas a uma base real, realizando extrações, cálculos agregados e manipulações de dados diretamente em um banco de dados em memória.**

### Etapas Desenvolvidas

* Importação da base TB_VENDAS_TAREFA.csv com pandas

* Criação de banco de dados em memória utilizando sqlite3

* Inserção dos dados na tabela TB_VENDAS

* Execução de consultas SQL, incluindo:

* Seleção de todas as colunas e registros

* Limitação de resultados (LIMIT)

* Cálculo de médias com AVG()

* Criação de colunas calculadas (valor total por venda)

* Cálculo de média do valor total vendido

### Discussões conceituais sobre:

* Diferenças entre SQL e Python na ciência de dados

* Bancos de dados relacionais vs. não relacionais

* Aplicabilidade prática do SQL em consultas rápidas

### Conceitos Trabalhados

* SELECT

* LIMIT

* Funções agregadas (AVG)

* Operações matemáticas em consultas

* Alias de colunas (AS)

* Integração Python + SQL

##  Como Executar

### Pré-requisitos
- Python 3.7+
- pip ou conda
- SQLite (incluído no Python)

### Instalação

```bash
# Clone o repositório
git clone https://github.com/GrizzoHenrique/BancoDeDadosSQL.git
cd BancoDeDadosSQL

# Crie um ambiente virtual (recomendado)
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate

# Instale as dependências
pip install -r requirements.txt
