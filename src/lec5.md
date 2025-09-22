---
marp: true
math: mathjax
theme: default
size: 4:3
paginate: true
backgroundColor: '#f4f6fa'
backgroundImage: url('https://marp.app/assets/hero-background.svg')
header: 'Lecture 5: Aggregate Expenditure and Output in Short Run'
footer: 'Fei Tan | Made on Earth by humans.'
style: |
  .logo {
    vertical-align: -0.2em;
  }
  section {
    color: #222;
    font-size: 24px;
    padding: 50px;
  }
  h1 {
    color: #003DA5;
    font-size: 38px;
    margin-bottom: 18px;
  }
  h2 {
    color: #003DA5;
    font-size: 30px;
    margin-bottom: 15px;
  }
  h3, h4, h5, h6 {
    color: #003DA5;
  }
  .slide-footer {
    color: #888;
  }
  .highlight {
    background-color: #ffeb3b;
    padding: 2px 4px;
    border-radius: 3px;
  }
  .identity-box {
    background-color: #f0f0f0;
    border-radius: 10px;
    padding: 12px;
    margin: 12px 0;
    text-align: center;
    border: 2px solid #ddd;
    font-size: 20px;
  }
  table {
    margin: 15px auto;
    border-collapse: collapse;
    font-size: 19px;
  }
  table th, table td {
    border: 2px solid #003DA5;
    padding: 8px 12px;
    text-align: center;
  }
  table th {
    background-color: #003DA5;
    color: white;
  }
  ul, ol {
    margin: 10px 0;
    padding-left: 25px;
  }
  li {
    margin: 6px 0;
    line-height: 1.5;
  }
  p {
    margin: 10px 0;
    line-height: 1.5;
  }
---

# Lecture 5: Aggregate Expenditure and Output in Short Run

**Instructor:** Fei Tan

<img src="images/github.png" width="30" height="30" class="logo"> @econdojo &nbsp;&nbsp;&nbsp;&nbsp; <img src="images/youtube.png" width="30" height="30" class="logo"> @BusinessSchool101 &nbsp;&nbsp;&nbsp;&nbsp; <img src="images/slu.png" width="30" height="30" class="logo"> Saint Louis University

**Course:** Macroeconomics 201  
**Date:** September 13, 2025

---

## The Road Ahead

1. [Aggregate Expenditure Model](#aggregate-expenditure)
2. [Determinants of Aggregate Expenditure](#determinants-of-consumption)
3. [Graphing Goods Market Equilibrium](#goods-market-equilibrium)
4. [Multiplier Effect](#graphing-multiplier-effect)
5. [Aggregate Demand Curve](#effect-of-price-level-change)

---

## Aggregate Expenditure

- Keynes identified four categories of expenditures

  - **consumption (C):** expenditure by consumers
  - **planned investment (I'):** expenditure by firms (NO unplanned changes in inventories)
  - **government purchases (G):** expenditure by gov't, not including transfer payments
  - **net exports (NX):** net expenditure by foreigners, exports (EX) $-$ imports (IM)

- **Goods market equilibrium/IS relation**

<div class="identity-box">

$$\underbrace{Y}_{\text{GDP}}=\underbrace{C+I'+G+NX}_{\text{aggregate expenditure (AE)}}$$

$$\Leftrightarrow\quad\text{actual investment}=\text{planned investment}$$

</div>

---

## Aggregate Expenditure Model

- A macro model that determines **short-run** output

  - relation between AE (total spending/demand) and GDP (total production/supply)
  - key assumptions: constant price level & no growth

- How AE model works

  - AE > GDP ⇒ inventories ↓ ⇒ (Y,N) ↑
  - AE < GDP ⇒ inventories ↑ ⇒ (Y,N) ↓
  - AE = GDP ⇒ inventories unchanged ⇒ goods market equilibrium

- GDP fluctuates due to changes in AE

---

## Determinants of Consumption

**Consumption function**

<div class="identity-box">

$$C=C(Y_D)=c_0+c_1Y_D,\qquad Y_D=Y-T$$

</div>

- Some notations

  - $C$ = consumption
  - $T$ = net taxes (taxes net of transfers)
  - $Y_D$ = disposable income
  - $c_1$ = marginal propensity to consume (MPC)
  - $c_0$ = autonomous consumption

- Other determinants: wealth, expected future income, **real interest rate (price of consumption today relative to tomorrow)**, price level

---

## Consumption Function

<img src="images/lec5/Fig1.JPG" width="90%" style="display: block; margin: 0 auto;">

- Relation b/w consumption and income (source: BEA)
- MPC = slope of consumption function

---

## U.S. Consumption

<img src="images/lec5/Fig2.png" width="90%" style="display: block; margin: 0 auto;">

- Real consumption, 1979-2017 (source: BEA)
- Consumption follows smooth, upward trend

---

## U.S. Investment

<img src="images/lec5/Fig3.png" width="95%" style="display: block; margin: 0 auto;">

- Real investment, 1979-2017 (source: BEA)
- Investment is subject to larger changes than consumption

---

## U.S. Government Purchases

<img src="images/lec5/Fig4.png" width="95%" style="display: block; margin: 0 auto;">

- Real government purchases, 1979-2017 (source: BEA)
- Government purchases grew steadily in most years

---

## U.S. Net Exports

<img src="images/lec5/Fig5.png" width="95%" style="display: block; margin: 0 auto;">

- Real net exports, 1979-2017 (source: BEA)
- Net exports were negative in most years

---

## Income, Consumption, and Saving

**Marginal propensity to consume/save**

<div class="identity-box">

$$\frac{\Delta Y_D}{\Delta Y_D}=\frac{\Delta C}{\Delta Y_D}+\frac{\Delta S}{\Delta Y_D}\quad\Rightarrow\quad 1=\text{MPC}+\text{MPS}$$

</div>

- Some remarks

  - $\Delta$ means 'change in'
  - MPC = $\Delta C/\Delta Y_D=\Delta C/\Delta Y$
  - $\Delta S/\Delta Y_D$ = marginal propensity to save (MPS)

- Example: consumption increases from $8,000 to $8,600 as national income increases from $9,000 to $10,000

$$\text{MPC}=\frac{\$8,600-\$8,000}{\$10,000-\$9,000}=0.6,\ \text{MPS}=1-\text{MPC}=0.4$$

---

## Solving for Equilibrium Output

**Equilibrium output**

<div class="identity-box">

$$Y=c_0+c_1(Y-T)+I+G+NX$$

$$\Rightarrow\quad Y=\frac{1}{1-c_1}[c_0+I+G+NX-c_1T]$$

</div>

- Some remarks

  - autonomous spending: $c_0+I+G+NX-c_1T$
  - multiplier: $1/(1-c_1)>1$ ($0<c_1<1$)

    **autonomous spending ↑ ⇒ Y↑ more than one for one**

- Example: $C=500+.5Y_D$, $Y_D=Y-T$, $T=600$, $I=300$, $G=2000$, and $NX=0$

$$Y=5000,\quad \text{multiplier}=2$$

---

## Goods Market Equilibrium

<img src="images/lec5/Fig6.png" width="65%" style="display: block; margin: 0 auto;">

- $45^{\circ}$-line diagram or Keynesian cross

---

## Goods Market Equilibrium (Cont'd)

<img src="images/lec5/Fig7.png" width="65%" style="display: block; margin: 0 auto;">

---

## Graphing Economic Recession

<img src="images/lec5/Fig8.png" width="55%" style="display: block; margin: 0 auto;">

- Paradox of thrift: short-run vs. long-run

---

## Graphing Multiplier Effect

<img src="images/lec5/Fig9.png" width="70%" style="display: block; margin: 0 auto;">

---

## Example: Multiplier Effect

| Round | Change in $I$ | Change in $C$ | Change in $Y$ |
|-------|---------------|---------------|---------------|
| 1     | $100          | $0            | $100          |
| 2     | $0            | $75           | $75           |
| 3     | $0            | $56           | $56           |
| ⋮     | ⋮             | ⋮             | ⋮             |

- Example: MPC = 0.75, $I↑$ by $100

- Calculate multiplier

<div class="identity-box">

$$\Delta Y=\$100\times(1+\text{MPC}+\text{MPC}^2+\text{MPC}^3+\cdots)$$

$$\Rightarrow\quad \text{multiplier}=\frac{\Delta Y}{\Delta I}=\frac{1}{1-\text{MPC}}=4\quad\text{(why?)}$$

</div>

- Higher MPC leads to higher multiplier

---

## Effect of Price Level Change

<img src="images/lec5/Fig10.jpg" width="90%" style="display: block; margin: 0 auto;">

- $P↑$ (↓) ⇒ real value of wealth ↓ (↑) ⇒ $C↓$ (↑)

- $P↑$ (↓) ⇒ exports ↓ (↑), imports ↑ (↓) ⇒ $NX↓$ (↑)

- $P↑$ (↓) with unchanged money supply ⇒ $i↑$ (↓) ⇒ $I↓$ (↑)

---

## Aggregate Demand Curve: First Pass

<img src="images/lec5/Fig11.png" width="90%" style="display: block; margin: 0 auto;">

- Inverse relation between price level and real GDP, known as aggregate demand curve

---

## Readings & Exercises

- Readings
  - HO: chapter 12
  - BJ: lecture 2 (sec. 1, 2, 3) (supplementary)

- Exercises
  - HO: problem 1.4, 2.11, 3.12, 4.9, 4.13, D12.1