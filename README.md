**Credit Risk Stress Testing Model**

This project simulates a full credit risk stress testing framework inspired by real-world applications in Global Risk Management at financial institutions. It demonstrates how quantitative analysts estimate expected loan losses under varying macroeconomic conditions using probabilistic modeling, structured data, and Python.

**Project Overview**

This model estimates Expected Loss (EL) for a synthetic loan portfolio under three macroeconomic scenarios:

**Baseline** — stable economic growth
**Moderate Stress** — slowing growth, rising unemployment
**Severe Stress** — recession-level shocks

**Expected Loss** (EL) is computed using the formula:

EL
=
PD
×
LGD
×
EAD
EL=PD×LGD×EAD
Where:

**PD** = Probability of Default (adjusted by scenario stress multipliers)
**LGD** = Loss Given Default (based on industry + collateral coverage)
**EAD** = Exposure at Default (proxied by loan size)

**Features**

Simulated 1,000-loan portfolio with industry, credit rating, collateral, and loan features
Scenario-driven macroeconomic shocks (GDP, interest rates, unemployment)
PD modeled using credit rating + scenario multipliers
LGD adjusted based on industry type and collateral adequacy
Full EL calculations and portfolio-level loss summaries
Clear, extensible structure for real-world stress testing analysis

**Technologies Used**

Python (pandas, NumPy)
Jupyter Notebook
Financial modeling techniques (Basel-style credit risk logic)
