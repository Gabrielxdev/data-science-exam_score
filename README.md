# 🎓 Student Exam Score Predictor

Este projeto é uma aplicação interativa desenvolvida com **Streamlit** e **Machine Learning**, que tem como objetivo prever a nota de um aluno em uma prova com base em seus hábitos e condições pessoais.

---

## 🎯 Propósito

A proposta do projeto é demonstrar, de forma prática, como técnicas de **regressão linear** podem ser aplicadas para gerar previsões reais, com base em dados comportamentais de estudantes. A ferramenta serve como exemplo educacional e pode ser adaptada para outros contextos de previsão.

---

## 🧠 Objetivo

* Prever a nota final de um estudante (**exam\_score**) com base em:

  * Horas de estudo por dia
  * Frequência às aulas
  * Avaliação da saúde mental
  * Horas de sono por noite
  * Se possui ou não trabalho de meio período

---

## 🚀 Tecnologias utilizadas

* [Pandas](https://pandas.pydata.org/)
* [Streamlit](https://streamlit.io/)
* [Scikit-learn](https://scikit-learn.org/)
* [NumPy](https://numpy.org/)
* [Joblib](https://joblib.readthedocs.io/)

---

## 📊 Dataset

O conjunto de dados contém registros fictícios de estudantes com os seguintes atributos:

* `study_hours_per_day`
* `attendance_percentage`
* `mental_health_rating`
* `sleep_hours_per_night`
* `part_time_job`
* `exam_score` (variável alvo)

---

## 📦 Como executar o projeto localmente

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio
```

2. Crie um ambiente virtual (opcional, mas recomendado):

```bash
python -m venv venv
venv\Scripts\activate   # Windows
source venv/bin/activate  # Linux/macOS
```

3. Instale as dependências:

```bash
pip install -r requirements.txt
```

4. Execute a aplicação:

```bash
streamlit run app.py
```

5. Acesse no navegador:

```
http://localhost:8501
```

---

## 📷 Exemplo do app

![Interface do app Streamlit](previsao_nota.png)

---

## 🛠️ Possíveis melhorias

* Adicionar outros modelos de ML para comparação (Decision Tree, Random Forest)
* Validar desempenho com métricas (RMSE, R²)
* Melhorar a interface visual com CSS customizado
* Permitir upload de CSV com múltiplos alunos para previsão em lote

---

## 📚 Créditos

Projeto desenvolvido por Gabriel Thiago como parte dos estudos em **Ciência de Dados** e **Machine Learning prático com Streamlit**.

---

## 📎 Licença

Este projeto é livre para uso educacional.
