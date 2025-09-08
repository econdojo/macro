---
marp: true
math: mathjax
theme: default
size: 4:3
paginate: true
backgroundColor: '#f4f6fa'
backgroundImage: url('https://marp.app/assets/hero-background.svg')
header: 'Lecture 3: Economic Growth, Financial System, and Business Cycles'
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

# Lecture 3: Economic Growth, Financial System, and Business Cycles

**Instructor:** Fei Tan

<img src="images/github.png" width="30" height="30" class="logo"> @econdojo &nbsp;&nbsp;&nbsp;&nbsp; <img src="images/youtube.png" width="30" height="30" class="logo"> @BusinessSchool101 &nbsp;&nbsp;&nbsp;&nbsp; <img src="images/slu.png" width="30" height="30" class="logo"> Saint Louis University

**Course:** Macroeconomics 201  
**Date:** September 7, 2025

---

## The Road Ahead

1. [Long-Run Economic Growth](#long-run-economic-growth)
2. [Saving, Investment, and Financial System](#saving-investment-and-financial-system)
3. [Business Cycle](#business-cycle)

---

## What is Economic Growth?

- A process by which rising productivity increases average standard of living

- How to measure average standard of living
  - real GDP **per capita** (most common)
  - production per person, adjusted for inflation

- We measure long-run economic growth by percentage increase in real GDP per capita over long periods

<div class="identity-box">

$$\text{growth rate}=\frac{Y_t-Y_{t-n}}{Y_{t-n}}\times 100\%,\quad \text{$n\sim$ decades}$$

</div>

---

## U.S. Economic Growth, 1900-2016

<img src="images/lec3/Fig1.png" width="90%" style="display: block; margin: 0 auto;">

- Growth in real GDP per capita (source: BEA)
- Average American can buy more than 8 times now

---

## Calculating Growth Rates

- Growth rate over long periods
  - annual growth rates: $g_1,g_2,\ldots,g_n$

    <div class="identity-box">

    $$Y_{t-n}\times(1+g_1)\times(1+g_2)\times\cdots\times(1+g_n)=Y_t$$

    </div>

  - average annual growth rate: $g$

    <div class="identity-box">

    $$Y_{t-n}\times(1+g)^n=Y_t$$

    </div>

  - A useful approximation: for small $n$

    <div class="identity-box">

    $$g\approx\frac{g_1+g_2+\cdots+g_n}{n}$$

    </div>

- Rule of 70: $\text{number of years to double}=\frac{70}{g}$

---

## What Determines Growth Rates?

- Labor productivity: quantity of goods and services produced by one worker or one hour of work

- What determines labor productivity
  - increases in capital per hour worked
  - technological change

- Potential GDP: level of real GDP attained when all firms are operating at capacity
  - "normal" hours & "normal" sized workforce
  - U.S. potential GDP: average annual rate of 3.2%

---

## Actual versus Potential GDP

<img src="images/lec3/Fig2.png" width="95%" style="display: block; margin: 0 auto;">

- U.S. actual and potential GDP (source: FRED)
- Actual GDP falls below potential during recessions

---

## What is Financial System?

- A system through which firms acquire funds from households
  - financial markets, e.g. bond/stock markets
  - financial intermediaries, e.g. banks, mutual funds

- Three key services of financial system
  - risk-sharing: portfolio diversification
  - liquidity: ease with which financial security can be exchanged for money
  - information: facts about borrowers and expected returns on financial securities

---

## Saving Equals Investment

**National income identity**

<div class="identity-box">

$$\underbrace{S}_{\text{national saving}}=\underbrace{Y-T-C}_{\text{private saving}}+\underbrace{T-G}_{\text{gov't saving}}=I+NX$$

</div>

- Some notations
  - $T$ = taxes net of transfers (net taxes)
  - $Y-T$ = disposable income
  - $S^p$ = private saving, $S^g$ = gov't (public) saving
  - $G-T$ = primary deficit/newly issued gov't debt

- Ways to raise national wealth
  - Closed economy: only accumulate capital ($S=I$)
  - Open economy: also net foreign investment ($NX$)

---

## Loanable Funds Market

<img src="images/lec3/Fig3.png" width="70%" style="display: block; margin: 0 auto;">

- Assume closed economy; single market for loanable funds
- Loanable funds market determines **real** interest rate

---

## Shift in Demand Curve

<img src="images/lec3/Fig4.png" width="65%" style="display: block; margin: 0 auto;">

- Effect of technological change: real interest rate ↑, loanable funds ↑
- Effects of expected future profits, corporate taxes?

---

## Shift in Supply Curve

<img src="images/lec3/Fig5.png" width="65%" style="display: block; margin: 0 auto;">

- Effect of budget deficit: real interest rate ↑, loanable funds ↓ (higher $G$ crowds out $I$)
- Effects of 401(k) retirement plan?

---

## Idealized vs. Actual Business Cycle

<img src="images/lec3/Fig6.png" width="90%" style="display: block; margin: 0 auto;">

- Alternating periods of expansions and recessions
- $(Y,N)$ ↑ (↓) during expansions (recessions)
- Recession: two consecutive quarters of declining real GDP
- National Bureau of Economic Research (NBER) Business Cycle Dating Committee

---

## Effect of Business Cycle

<img src="images/lec3/Fig7.png" width="100%" style="display: block; margin: 0 auto;">

- Effect of business cycles on inflation (source: BLS)

---

## Effect of Business Cycle (Cont'd)

<img src="images/lec3/Fig8.png" width="100%" style="display: block; margin: 0 auto;">

- Effect of business cycles on unemployment (source: BLS)

---

## Great Moderation

<img src="images/lec3/Fig9.png" width="90%" style="display: block; margin: 0 auto;">

- Annual fluctuations in real GDP (source: BEA)
- Reduction in volatility of business cycles since mid-1980s

---

## Readings & Exercises

- Readings
  - HO: chapter 10
  - BJ: lecture 2 (sec. 4) (supplementary)

- Exercises
  - HO: problem 1.8, 2.7, 2.8, 2.10, D10.1, D10.2
