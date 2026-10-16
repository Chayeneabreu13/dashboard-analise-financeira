# 💰 Dashboard de Análise Financeira

Dashboard em Power BI para analisar receitas, despesas e margem de lucro de uma empresa, identificando os componentes de maior e menor desempenho para apoiar o planejamento estratégico.

![Dashboard](imagens/dashboard.png)


---

## 🎯 Objetivo

Responder perguntas de negócio como:

- A empresa é lucrativa? Qual a margem?
- De onde vem a receita e para onde vai a despesa?
- Receitas e despesas estão crescendo no mesmo ritmo?
- Quais componentes pedem atenção?

## 📊 Indicadores

- Total de receitas
- Total de despesas
- Margem de lucro
- Receitas por componente
- Despesas por componente (comparadas à média)
- Receitas e despesas por ano, com hierarquia Tipo > Componente

## 🔍 Principais insights

**Visão geral**

| Indicador | Valor |
|---|---|
| Receitas | R$ 1,92 Mi |
| Despesas | R$ 1,15 Mi |
| Lucro | R$ 0,77 Mi |
| Margem de lucro | 39,96% |

**Receitas**

- **Vendas** é a principal fonte: cerca de R$ 1,36 Mi, aproximadamente **71% da receita total**.
- Licenciamento (R$ 232 mil) é a segunda maior fonte.
- **Franquias** é o único componente em queda: de R$ 25 mil (2019) para R$ 16,6 mil (2022), cerca de **-34%**.

**Despesas**

- Maiores componentes: **Administrativo** (R$ 462 mil), **Tecnologia** (R$ 277 mil) e **Salários** (R$ 241 mil).
- **Salários** foi o que mais cresceu: de R$ 40 mil (2019) para R$ 124 mil (2022).

**Evolução 2019 → 2022**

| Ano | Receitas | Despesas | Margem |
|---|---|---|---|
| 2019 | R$ 560 mil | R$ 288 mil | ~48,7% |
| 2020 | R$ 604 mil | R$ 370 mil | ~38,6% |
| 2022 | R$ 756 mil | R$ 495 mil | ~34,5% |

- Receitas cresceram cerca de **35%**, enquanto as despesas cresceram cerca de **72%**.
- Resultado: a **margem caiu de ~49% para ~35%** no período.

## 💡 Recomendações

1. **Controlar as despesas com Salários e Administrativo**, que puxam o crescimento dos custos e a queda da margem.
2. **Reduzir a dependência de Vendas** (~71% da receita), investindo em outras fontes como Licenciamento.
3. **Investigar a queda em Franquias** para decidir se vale recuperar ou redirecionar o investimento.
4. **Acompanhar a margem ano a ano** com uma meta mínima definida.

## 🛠️ Ferramentas

- Power BI
- DAX (medidas: TotalReceitas, TotalDespesas, Lucro, Margem de Lucro)
- Power Query (tratamento dos dados)

## 🗂️ Dados

Dataset **fictício** disponibilizado no curso de Power BI da Data Science Academy, usado para fins didáticos. O dashboard, o layout e as conclusões foram desenvolvidos por mim.

> Observação: o dataset não contém dados do ano de 2021.

## 📁 Estrutura do repositório

- Dashboard Financeiro.pbix
- dados/
- imagens/dashboard.png
- README.md

## 👩‍💻 Autora

**Chayene Abreu**

🔗 LinkedIn: (www.linkedin.com/in/chayene-abreu)
