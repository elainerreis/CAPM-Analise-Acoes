# Análise de Ações com CAPM

Este projeto consiste na análise de ações do mercado brasileiro utilizando o modelo CAPM (Capital Asset Pricing Model).  
O objetivo foi calcular o risco e o retorno excedente de ativos em relação ao mercado (Ibovespa) e construir uma carteira potencialmente mais eficiente.

## 📋 Descrição do Projeto

- Seleção inicial de 20 ações de ações com base em filtros fundamentalistas:
  - P/L ≤ 15
  - P/VP ≤ 2
  - P/L * P/VP ≤ 22,5
  - Dívida Líquida/EBIT ≤ 5
  - Análise adicional de ROE, Margem Líquida e Valorização no último ano.
  
- Estimação dos parâmetros do modelo CAPM:
  - **Beta (β)**: Mede a volatilidade da ação em relação ao mercado. Valores superiores a 1 sugerem maior volatilidade que o mercado, enquanto valores inferiores a 1 indicam menor volatilidade.
  - **Alpha (α)**: Mede o retorno excedente além do previsto pelo risco sistemático. Um alfa positivo sugere que o ativo superou as expectativas ajustadas ao risco.
  
- Avaliação dos resultados para identificar ativos atrativos em termos de risco e retorno.

## 🛠️ Tecnologias Utilizadas

- **Python 3.11**
- **Pandas** – Manipulação de dados
- **NumPy** – Cálculos matemáticos
- **Matplotlib** e **Seaborn** – Visualização gráfica
- **Statsmodels** – Estimação de regressão linear (CAPM)

## 📈 Resultados

- Identificação de ações com Betas e Alphas adequados à estratégia de investimento.
- Discussão sobre significância estatística limitada devido ao pequeno número de observações (3 anos de dados).
- Verificação do retorno médio da carteira inicial e final com as ações selecionadas.
## 📎 Como executar

Clone o repositório:

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
