---
marp: true
math: mathjax
theme: default
size: 4:3
paginate: true
backgroundColor: '#f4f6fa'
backgroundImage: url('https://marp.app/assets/hero-background.svg')
header: 'Lecture 9: IS-LM Model'
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
    table-layout: fixed;
    width: 80%;
  }
  table th, table td {
    border: 2px solid #003DA5;
    padding: 8px 12px;
    text-align: center;
    width: 25%;
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

# Lecture 9: IS-LM Model

**Instructor:** Fei Tan

<img src="images/github.png" width="30" height="30" class="logo"> @econdojo &nbsp;&nbsp;&nbsp;&nbsp; <img src="images/youtube.png" width="30" height="30" class="logo"> @BusinessSchool101 &nbsp;&nbsp;&nbsp;&nbsp; <img src="images/slu.png" width="30" height="30" class="logo"> Saint Louis University

**Course:** Macroeconomics 101  
**Date:** October 25, 2025

---

## The Road Ahead

1. [Goods Market and IS Relation](#goods-market-equilibrium-revisited)
2. [Financial Market and LM Relation](#financial-market-equilibrium-revisited)  
3. [IS-LM Model](#is-lm-model)

---

## Goods Market Equilibrium Revisited

### IS relation: $(Y,i)$

<div class="identity-box">

$$\underbrace{Y}_{\text{GDP}}=\underbrace{C(Y-T)+I(Y,i)+G+NX}_{\text{aggregate expenditure (AE)}}$$

</div>

- Investment ($I$) depends on two main factors:

    - level of sales, equal to production ($Y$) under no inventory investment
    - interest rate ($i$), **cost/price of borrowing**

- Some remarks:

    - given $i$, $Y\uparrow$ $\Rightarrow$ $(C,I)\uparrow$ $\Rightarrow$ AE $\uparrow$
    - empirics: $Y\uparrow$ $\Rightarrow$ $C+I\uparrow$ less than one for one

---

## Equilibrium $Y$ Given $i$

<img src="images/lec10/Fig1.jpg" width="70%" style="display: block; margin: 0 auto;">

---

## Deriving IS Curve

<img src="images/lec10/Fig2.jpg" width="35%" style="display: block; margin: 0 auto;">

---

## Shift of IS Curve

<img src="images/lec10/Fig3.jpg" width="70%" style="display: block; margin: 0 auto;">

- Given $i$, $T\uparrow$ $\Rightarrow$ $C\downarrow$ $\Rightarrow$ $Y\downarrow$ through multiplier
- IS curve shifts to left

---

## Financial Market Equilibrium Revisited

### LM relation: $(Y,i)$

<div class="identity-box">

$$M^s=M^d=\$Y\times L(i)\quad\Rightarrow\quad\frac{M^s}{P}=\frac{M^d}{P}=Y\times L(i)$$

</div>

- Money demand ($M^d$) depends on two main factors:

    - level of transactions, assumed to be proportional to nominal GDP ($\$Y$)
    - nominal interest rate ($i$) on bonds, hence **opportunity cost/price of holding money**

- Notations:

    - $P$ = price level, e.g. GDP deflator/CPI
    - $M^s/P$ = real money supply
    - $M^d/P$ = real money demand

---

## Equilibrium $i$ Given $Y$

<img src="images/lec10/Fig4.jpg" width="70%" style="display: block; margin: 0 auto;">

---

## Deriving LM Curve

<img src="images/lec10/Fig5.jpg" width="90%" style="display: block; margin: 0 auto;">

---

## Shift of LM Curve

<img src="images/lec10/Fig6.jpg" width="65%" style="display: block; margin: 0 auto;">

- Given $(Y,P)$, $M^s\uparrow$ $\Rightarrow$ $M^s/P>M^d/P$ $\Rightarrow$ $i\downarrow$
- LM curve shifts down

---

## IS-LM Model

<img src="images/lec10/Fig7.jpg" width="70%" style="display: block; margin: 0 auto;">

---

## Effects of Fiscal Contraction

<img src="images/lec10/Fig8.jpg" width="70%" style="display: block; margin: 0 auto;">

- Fiscal contraction/consolidation: decrease in $G-T$
- Consider $T\uparrow$ $\Rightarrow$ IS curve $\leftarrow$, LM curve unchanged
- In equilibrium, $Y\downarrow$, $i\downarrow$ (Explain!)

---

## Effects of Monetary Expansion

<img src="images/lec10/Fig9.jpg" width="65%" style="display: block; margin: 0 auto;">

- Monetary expansion: increase in $M^s$ (How?)
- $M^s\uparrow$ $\Rightarrow$ IS curve unchanged, LM curve $\downarrow$
- In equilibrium, $Y\uparrow$, $i\downarrow$ (Explain!)

---

## Readings & Exercises

- Readings
  
  - BJ: lecture 4

- Exercises
  
  - Graphically illustrate effects of fiscal expansion or monetary contraction on equilibrium output and interest rate. EXPLAIN your results.