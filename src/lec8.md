---
marp: true
math: mathjax
theme: default
size: 4:3
paginate: true
backgroundColor: '#f4f6fa'
backgroundImage: url('https://marp.app/assets/hero-background.svg')
header: 'Lecture 8: Monetary Policy'
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

# Lecture 8: Monetary Policy

**Instructor:** Fei Tan

<img src="images/github.png" width="30" height="30" class="logo"> @econdojo &nbsp;&nbsp;&nbsp;&nbsp; <img src="images/youtube.png" width="30" height="30" class="logo"> @BusinessSchool101 &nbsp;&nbsp;&nbsp;&nbsp; <img src="images/slu.png" width="30" height="30" class="logo"> Saint Louis University

**Course:** Macroeconomics 201  
**Date:** October 6, 2025

---

## The Road Ahead

1. [What Is Monetary Policy](#what-is-monetary-policy)
2. [Money Market and Federal Funds Rate](#money-market-equilibrium-revisited)
3. [Monetary Policy and Economic Activity](#effects-of-monetary-policy)

---

## What Is Monetary Policy?

- Federal reserve system
  
  - established in 1914 as lender of last resort to prevent panics
  - central bank in U.S., bankers' bank
  - make discount loans to banks, charge discount rate

- Nowadays Fed manages policy targets (money supply & interest rates) to achieve macro objectives
  
  - <span class="highlight">dual mandate</span>: price stability & high employment
  - stability of financial markets & institutions
  - long-run economic growth

- Fed's conventional policy tools, e.g. open market operations, discount policy, reserve requirements

---

## Money Market Equilibrium Revisited

<img src="images/lec8/Fig1.png" width="68%" style="display: block; margin: 0 auto;">

- $M^s\uparrow$ ⇒ $M^d<M^s$ ⇒ $i\downarrow$ to restore equilibrium

- Short-term nominal rate v.s. long-term real rate

---

## Federal Funds Rate

<img src="images/lec8/Fig2.png" width="90%" style="display: block; margin: 0 auto;">

- Interest rate banks charge each other for overnight loans

- Target rate (Fed) v.s. effective rate (federal funds market)

- Open market purchase (sale) ⇒ reserves supply $\uparrow$ ($\downarrow$) ⇒ effective rate $\downarrow$ ($\uparrow$) ⇒ other short/long-term rates $\downarrow$ ($\uparrow$)

---

## Effects of Monetary Policy

<img src="images/lec8/Fig3.png" width="90%" style="display: block; margin: 0 auto;">

- Expansionary (contractionary) monetary policy
  
  - $i\downarrow$ ($\uparrow$) ⇒ borrowing cost $\downarrow$ ($\uparrow$) ⇒ $C,I\uparrow$ ($\downarrow$)
  - $i\downarrow$ ($\uparrow$) ⇒ $ depreciates (appreciates) ⇒ $NX\uparrow$ ($\downarrow$)

- AD curve shifts to right (left)

---

## Effects of Monetary Policy (Cont'd)

<img src="images/lec8/Fig4.png" width="80%" style="display: block; margin: 0 auto;">

- Expansionary/loose monetary policy to fight recession

---

## Effects of Monetary Policy (Cont'd)

<img src="images/lec8/Fig5.png" width="80%" style="display: block; margin: 0 auto;">

- Contractionary/tight monetary policy to fight inflation

---

## Monetary Policy Rule

### Taylor rule

<div class="identity-box">

$$i_t^*=r_n+\pi_t+a(\pi_t-\pi^*)-b(u_t-u_n)$$

$$\Rightarrow\quad i_t^*=r_n+\pi^*+\color{red}(a+1)\color{black}(\pi_t-\pi^*)-b(u_t-u_n)$$

</div>

Some remarks

- suggested by John Taylor for setting target rate $i_t^*$
- $r_n$: natural real rate, consistent w/ potential GDP
- $\pi_t-\pi^*$: gap b/w inflation and target
- $u_t-u_n$: gap b/w unemployment and natural rate
- counter-cyclical policy: $a>0$ and $b>0$
- Taylor principle: $\pi_t\uparrow$ ⇒ $i_t^*\uparrow$ more than one for one

---

## Readings & Exercises

- Readings
  
  - HO: chapter 15
  - BJ: lecture 20 (supplementary)

- Exercises
  
  - HO: problem 1.2, 2.5, 3.6, 4.4, 4.5, D15.2
  - Write down Taylor rule and discuss how it explains implementation of monetary policy.