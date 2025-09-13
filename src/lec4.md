---
marp: true
math: mathjax
theme: default
size: 4:3
paginate: true
backgroundColor: '#f4f6fa'
backgroundImage: url('https://marp.app/assets/hero-background.svg')
header: 'Lecture 4: Economic Growth Model'
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

# Lecture 4: Economic Growth Model

**Instructor:** Fei Tan

<img src="images/github.png" width="30" height="30" class="logo"> @econdojo &nbsp;&nbsp;&nbsp;&nbsp; <img src="images/youtube.png" width="30" height="30" class="logo"> @BusinessSchool101 &nbsp;&nbsp;&nbsp;&nbsp; <img src="images/slu.png" width="30" height="30" class="logo"> Saint Louis University

**Course:** Macroeconomics 201  
**Date:** September 13, 2025

---

## The Road Ahead

1. [Measuring Standard of Living](#standard-of-living-revisited)
2. [Economic Growth Model](#economic-growth-model)

---

## Standard of Living Revisited

- Cross-country comparison of standard of living
  - purchasing power parity (PPP) numbers
  - GDP/GDP per capita constructed with common set of prices for all countries
  - downloadable from Penn World Tables

- Why using PPP numbers
  - exchange rate vary a lot
  - systematic differences in prices across countries

- We measure long-run economic growth by percentage increase in PPP numbers over long periods

<div class="identity-box">

$$\text{growth rate}=\frac{Y_t-Y_{t-n}}{Y_{t-n}}\times 100\%,\quad \text{$n\sim$ decades}$$

</div>

---

## Growth in Rich Countries

<img src="images/lec4/Fig1.jpg" width="90%" style="display: block; margin: 0 auto;">

- Large increase in output per capita
- Convergence of output per capita across countries

---

## Economic Growth Model

**Aggregate production function**

<div class="identity-box">

$$Y=F(K,N)\qquad \text{(e.g. $Y=AN$)}$$

</div>

- Notations
  - $Y$ = aggregate output
  - $K$ = aggregate capital
  - $N$ = aggregate employment

- Three assumptions
  - constant returns to scale

  <div class="identity-box">

  $$xY=F(xK,xN)\qquad \text{for any $x$}$$

  </div>

  - decreasing returns to capital & labor

---

## Economic Growth Model (Cont'd)

**Per capita production function**

<div class="identity-box">

$$\frac{Y}{N}=F\left(\frac{K}{N},\frac{N}{N}\right)=F\left(\frac{K}{N},1\right)\qquad \text{(set $x=1/N$)}$$

</div>

- Notations
  - $Y/N$ = output per capita
  - $K/N$ = capital per capita

- Sources of economic growth
  - capital accumulation
  - technological progress

---

## Capital Accumulation

<img src="images/lec4/Fig2.jpg" width="80%" style="display: block; margin: 0 auto;">

- Capital accumulation cannot sustain growth (why?)

---

## Technological Progress

<img src="images/lec4/Fig3.jpg" width="70%" style="display: block; margin: 0 auto;">

- Sustained growth requires sustained technological progress

---

## Readings & Exercises

- Readings
  - HO: chapter 11
  - BJ: lecture 8 (supplementary)

- Exercises
  - HO: problem 2.8, 2.9
  - Let production function be $Y=\sqrt{K}\sqrt{N}$. Compute output when $K=49$ and $N=81$. If capital and labor double, what is output? It is constant returns to scale? Compute $Y/N$ when $K/N=4$.