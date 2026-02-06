## 📊Data Salary Analytics Dashboard

Interactive Data Analysis with Python & Streamlit

**Dashboard em produção:**  
https://projeto-imersao-dados.streamlit.app/

Dashboard analítico desenvolvido em Python para exploração e visualização de dados salariais do mercado de Dados.  
O projeto transforma um dataset real em insights claros e interativos, permitindo análises comparativas por senioridade, tipo de contrato, modelo de trabalho, tamanho da empresa e localização geográfica.

Projeto desenvolvido durante a **Imersão Dados (Alura)**, com foco em análise de dados, visualização, organização de código e entrega de valor.

---

## Demonstração Visual do Dashboard

### Proporção dos Tipos de Trabalho

Visualização da distribuição entre presencial, remoto e híbrido, permitindo identificar padrões de modelo de trabalho no mercado de dados.

![Proporção dos tipos de trabalho](./assets/proporcao_tipos_trabalho.png)

---

### Salário Médio de Cientista de Dados por País

Mapa interativo que evidencia a variação salarial global, facilitando comparações entre diferentes países e regiões.

![Salário médio por país](./assets/salario_medio_por_pais.png)

---

## Objetivo do Projeto

Demonstrar, na prática, competências técnicas e analíticas aplicáveis ao mercado, incluindo:

- Análise exploratória de dados reais  
- Construção de dashboards interativos  
- Comunicação visual de informações complexas  
- Organização e versionamento de projetos  
- Uso de ferramentas amplamente adotadas na área de Dados  

---

## Principais Funcionalidades

- Filtros interativos por:
  - Ano
  - Senioridade
  - Tipo de contrato
  - Modelo de trabalho
  - Tamanho da empresa
- Visualização de:
  - Salário médio
  - Distribuição salarial
  - Comparações entre categorias
- Gráficos interativos e responsivos
- Interface simples, objetiva e orientada à experiência do usuário

---

## Tecnologias e Ferramentas

- Python
- Streamlit
- Pandas
- Plotly
- Git & GitHub

---

## Destaques Técnicos

- Limpeza e preparação de dados utilizando **Pandas**
- Análise exploratória focada em **indicadores de mercado de Dados**
- Criação de visualizações interativas com **Plotly**
- Desenvolvimento de dashboard web com **Streamlit**
- Organização do projeto seguindo boas práticas de versionamento
- Deploy da aplicação em ambiente público para acesso via navegador

---

## Possíveis Evoluções

- Implementar filtros avançados por senioridade, país e tipo de contrato
- Adicionar séries temporais para análise de evolução salarial ao longo dos anos
- Integrar novas fontes de dados para enriquecer as análises
- Criar autenticação de usuários para dashboards personalizados
- Refatorar a aplicação em módulos para maior escalabilidade

---

## Estrutura do Projeto

```text
projeto-imersao-dados/
│
├── app.py
├── dados_imersao_final.csv
├── requirements.txt
├── assets/
│   ├── README.md
│   ├── proporcao_tipos_trabalho.png
│   └── salario_medio_por_pais.png
└── README.md
```

---

## Como executar localmente

### Pré-requisitos

- Python 3.8 ou superior

### Passo a passo
### 1️⃣ Clonar o repositório

```bash
git clone https://github.com/seu-usuario/projeto-imersao-dados.git
cd projeto-imersao-dados
```

---

## 2️⃣ Criar e ativar o ambiente virtual

```bash
python -m venv .venv
```

### Windows

```bash
.venv\Scripts\activate
```

### Linux / macOS

```bash
source .venv/bin/activate
```
---

## 3️⃣ Instalar as dependências

```bash
pip install -r requirements.txt
```

---

## 4️⃣ Executar a aplicação

```bash
streamlit run app.py
```

Após a execução, a aplicação será aberta automaticamente no navegador padrão.

---

## Autor

**Gabriel Godoi**  
Estudante e entusiasta da área de Dados, com foco em análise, visualização e construção de dashboards interativos em Python.  
Projeto desenvolvido para fins educacionais e de portfólio.
