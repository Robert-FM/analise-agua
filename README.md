# Machine Learning Aplicado à Qualidade da Água

Projeto de análise de qualidade da água utilizando Python e técnicas de Machine Learning para tratamento, análise exploratória e treinamento de modelos preditivos.

---

## 📌 Objetivo

Este projeto tem como objetivo realizar:

- Tratamento e organização de dados de qualidade da água;
- Análise exploratória dos dados;
- Construção e avaliação de modelos de Machine Learning;
- Salvamento e deploy do melhor modelo treinado.

---

## 📂 Estrutura do Projeto

```bash
ANALISE-AGUA/
│
├── .venv/                     
│
├── analise-dados/
│   └── analise-dados.ipynb
│
├── data/
│   ├── 01-raw/
│   │   └── water_potability.csv
│   │
│   └── 02-processed/
│       └── dados-agua-tratados.csv
│
├── deploy/
│   └── melhor_modelo.pkl
│
├── modelos/
│   ├── catboost_info/
│   └── ml-analise.ipynb
│
├── .gitignore
├── .python-version
├── anotacao.txt
├── pyproject.toml
├── README.md
└── uv.lock
```

---

## ⚙️ Tecnologias Utilizadas

- Python 3.14
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- CatBoost
- LightGBM
- Gradient Boosting
- XGBoost
- Jupyter Notebook
- UV

---

## 🚀 Como Executar o Projeto

### 1️⃣ Clonar o repositório

```bash
git clone https://github.com/Robert-FM/analise-agua.git
cd analise-agua
```

---

### 2️⃣ Criar e ativar o ambiente virtual

#### Linux/macOS

```bash
python -m venv .venv
source .venv/bin/activate
```

#### Windows

```bash
python -m venv .venv
.venv\Scripts\activate
```

---

### 3️⃣ Instalar as dependências

Caso utilize UV:

```bash
uv sync
```

Ou com pip:

```bash
pip install -r requirements.txt
```

---

## 📊 Fluxo do Projeto

### 🔹 1. Dados Brutos

Os dados originais ficam em:

```bash
data/01-raw/
```

---

### 🔹 2. Tratamento dos Dados

Os dados tratados são armazenados em:

```bash
data/02-processed/
```

---

### 🔹 3. Análise Exploratória

Notebook utilizado:

```bash
analise-dados/analise-dados.ipynb
```

Etapas realizadas:

- Limpeza dos dados;
- Verificação de valores ausentes;
- Estatísticas descritivas;
- Visualizações gráficas;
- Correlação entre variáveis.

---

### 🔹 4. Treinamento de Modelos

Notebook utilizado:

```bash
modelos/ml-analise.ipynb
```

Modelos utilizados:

- Random Forest
- CatBoost
- CatBoost
- LightGBM
- Gradient Boosting

---

### 🔹 5. Salvamento do Melhor Modelo

O melhor modelo é salvo em:

```bash
deploy/
```

Formato do modelo:

```bash
.pkl
```

---

## 📈 Possíveis Melhorias Futuras

- Criação de API com FastAPI ou Flask;
- Deploy em nuvem;
- Dashboard interativo;
- Pipeline automatizado;
- Monitoramento do modelo;
- Validação cruzada avançada.

---

## 🧠 Dataset

Dataset utilizado para análise de potabilidade da água.

### Atributos do dataset

- pH
- Hardness
- Solids
- Chloramines
- Sulfate
- Conductivity
- Organic Carbon
- Trihalomethanes
- Turbidity

### Variável alvo

```python
Potability
```

---

## 👨‍💻 Autor

Robert Melo

🔗 LinkedIn: https://www.linkedin.com/in/robertdemelo/

🐍 Python | IA | Machine Learning | LangChain | Data Science

---

## 📄 Licença

Este projeto está sob a licença MIT.