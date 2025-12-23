# 📊 Análise do Setor de Marketing – Empresa X

## 📊 Contexto de Negócio

Este projeto simula um cenário real de uma empresa comercial que investe em diferentes canais de marketing e precisa decidir **como alocar melhor seu orçamento para maximizar retorno em vendas**.

No dia a dia corporativo, gestores de marketing enfrentam o desafio de justificar investimentos em múltiplos canais — como mídia digital e mídia tradicional — sem clareza total sobre **quais canais realmente geram impacto nos resultados do negócio**.

Os dados utilizados representam **investimentos realizados em diferentes meios de comunicação e o retorno obtido em vendas**, refletindo um problema comum enfrentado por equipes de marketing, BI e análise de dados: transformar gastos em decisões estratégicas orientadas por dados.

---

## 📌 Objetivo da Análise

O objetivo desta análise é **avaliar o impacto dos investimentos em diferentes canais de marketing sobre as vendas**, identificando quais meios apresentam maior potencial de retorno e fornecendo subsídios analíticos para **decisões de realocação de orçamento e otimização de estratégias de marketing**.

A análise busca apoiar decisões como:

* Priorização de canais mais eficientes
* Redução de investimentos com baixo retorno
* Planejamento de cenários futuros de investimento

---

## 🛠️ Ferramentas Utilizadas

As análises foram realizadas utilizando:

* **Python (Pandas, NumPy)** → limpeza, manipulação e estruturação dos dados
* **Matplotlib e Seaborn** → visualização de padrões, tendências e relações entre investimentos e vendas
* **Scikit-learn** → construção e avaliação de modelos de regressão como apoio à análise preditiva
* **XGBoost** → modelagem preditiva avançada para estimar retornos de investimento
* **Jupyter Notebook** → documentação do processo analítico e reprodutibilidade

As ferramentas foram utilizadas como suporte à análise e à tomada de decisão, mantendo o foco no problema de negócio.

---

## 📈 Principais Insights

* **O investimento em Jornal apresentou baixo impacto nas vendas**, indicando que este canal possui menor eficiência quando comparado aos demais, o que sugere possível desperdício de orçamento.

* **Facebook demonstrou forte relação com o volume de vendas**, sugerindo que investimentos nesse canal tendem a gerar retorno mais previsível e consistente.

* **YouTube apresentou o maior retorno marginal sobre o investimento**, especialmente quando analisado por meio de modelos preditivos, indicando alto potencial de escalabilidade.

* **Modelos não lineares capturaram melhor o comportamento dos dados**, evidenciando que a relação entre investimento e retorno não é puramente linear e depende de combinações entre canais.

Esses insights reforçam a importância de utilizar dados históricos para avaliar eficiência de canais e evitar decisões baseadas apenas em intuição.

---

## 🎯 Possíveis Decisões

Com base nos insights obtidos, seria possível:

* **Reduzir ou descontinuar investimentos em Jornal**, redirecionando o orçamento para canais com maior impacto comprovado.

* **Priorizar investimentos em YouTube e Facebook**, maximizando o retorno sobre o orçamento de marketing.

* **Utilizar modelos preditivos para simular cenários de investimento**, apoiando o planejamento estratégico de campanhas futuras.

* **Apoiar decisões de orçamento com base em dados**, reduzindo riscos e aumentando a eficiência das ações de marketing.

---

## ▶️ Como Executar o Projeto

1. Clone o repositório:

```bash
git clone https://github.com/Ogarit/Analise_do_Setor_de_Marketing-Empresa_Ficticia.git
```

2. Instale as dependências:

```bash
pip install -r requirements.txt
```

3. Execute o script principal:

```bash
python main.py
```

4. Os resultados da análise serão apresentados por meio de visualizações e métricas geradas ao longo da execução.
