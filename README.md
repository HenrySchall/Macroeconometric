# Macroeconometrics

![Gere uma imagem sobre macroeconometria 20-02-2025 at 06-30-35](https://github.com/user-attachments/assets/99ef8ada-2357-47c9-a2c3-0cf2e57d471a)

> Macroeconomists seek to understand specific economic phenomena by formulating models (simplified representations of reality). These models are based on the formulation of hypotheses about how the economy works, that is, the behavior of economic agents within the market.

### Macroeconomic Model of the Brazilian Central Bank 

1. Small-scale semi-structural models
2. Vector Autoregressive (VAR) Models
3. Leading and core inflation indicators
6. Medium semi-structural model (PAGODE)
7. Medium-sized Micro-Founded Model (SAMBA)

### Small-Scale Semi-Structural Models

> In 1990, macroeconomic theory began to be based on the neoclassical synthesis or new macroeconomic consensus. The implications of this were the development of small structural models, which made it possible to estimate the lags in the effect of changes in the monetary policy instrument on prices.

Model Assumptions: 
- Inflation depends on the real interest rate
- Nominal base interest rate is the instrument of monetary policy
- Agents' expectations can be backward-looking (past information) or forward-looking (future expectations)
- There are transmission mechanisms in monetary policy decisions and they have transmission lags

> The new consensus or new Keynesianism admits short-term subequilibria, derived from market failures, that is, the output gap may be non-zero in the short term. Therefore, the BC's small-scale models seek to capture the transmission mechanisms of monetary policy decisions, as well as the lags involved, and are composed of:

- IS Curve (Demand)
- Phillips Curve (Supply)
- Interest Rate Parity (Contact with the external sector)
- Taylor Rule (Monetary Policy Decisions)

> Interest Rate Parity ou Condição de paridade descoberta da taxa de juros é um conceito que descreve a relação entre as taxas de juros de dois países e as taxas de câmbio esperadas entre suas moedas. Essa condição é importante para entender como as taxas de juros e as expectativas de câmbio influenciam os fluxos de capital entre os países.

#### Matematicamente: 
Curva IS -> $Ht = \beta0 - \beta1(it - Etπt+1 - r*) + β2Θt−1 + β3Ψt−1 + εt$

- Ht = Hiato do produto
- it = Taxa de juros nominal
- Etπt+1 = Expectativa em t para a inflação em t + 1
- r∗ = Taxa de juros neutra
- Θt−1 = Taxa de câmbio real
- Ψt−1 = Necessidades de financiamento do setor público
- εt = Choque de demanda

Curva de Phillips -> $πt = α0 + α1πt−1 + α2Etπt+1 + α3ht−1 + α4∆εt + εt$

- πt = Inflação
- ∆εt = Primeira diferença da taxa de câmbio nominal
- εt = Choque de oferta

Interest Rate Parity -> $∆εt = φ0 φ1(it − it*) + φ2xt + εt$

- (it − it*) = diferencial de juros
- xt = prêmio de risco
- εt = choque externo

Regra de Taylor -> $it = ω0 + ω1it−1 + ω2(Etπt+1 − π∗) + ω3ht + ω4∆εt + εt$

- π∗ = Meta de inflação
- εt = ruído branco

### Apêndice

### Bibliographical References:
 W.H. Greene. Econometric Analysis. Pearson Education, 2003.
C. A. Sims. Macroeconometrics and reality. Econometrica,
E. J. A. Lima, F. Araujo, and J. R. Costa e Silva. Previsáo e
 Modelos Macroeconômicos no banco central do brasil. Dez anos
 de metas para inflação no Brasil, 2010.
  J. M. Wooldridge. Introductory Econometrics: A Modern Approach.
 Editora Cengage, 2013
