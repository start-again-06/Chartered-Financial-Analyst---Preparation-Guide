# Chartered Financial Analyst (CFA) Level 1 Notes  
## Fixed Income and Derivatives

---

## Overview

This repository provides structured and concept-driven notes for the Chartered Financial Analyst (CFA) Level 1 curriculum, focusing on Fixed Income and Derivatives. The material is designed not only for theoretical understanding but also for developing strong analytical and problem-solving skills through mathematical modeling. The content integrates financial intuition with rigorous quantitative frameworks, enabling a deeper understanding of how debt markets and derivative instruments are priced, analyzed, and used in practice.

---

## Fixed Income

Fixed Income forms the backbone of global financial markets and focuses on valuation, interest rate behavior, and credit risk.

---

### Bond Pricing and Valuation

The value of a bond is the present value of all future cash flows:

$$
P = \sum_{t=1}^{N} \frac{C}{(1 + y)^t} + \frac{FV}{(1 + y)^N}
$$

Where:
- \( P \) = Bond price  
- \( C \) = Coupon payment  
- \( y \) = Yield to maturity  
- \( FV \) = Face value  
- \( N \) = Number of periods  

---

### Yield Measures

Effective Annual Yield:

$$
EAY = \left(1 + \frac{y}{n}\right)^n - 1
$$

Yield Spread:

$$
\text{Spread} = y_{\text{bond}} - y_{\text{benchmark}}
$$

---

### Term Structure of Interest Rates

Spot rate pricing:

$$
P = \sum_{t=1}^{N} \frac{CF_t}{(1 + S_t)^t}
$$

Forward rate:

$$
f_{1,1} = \frac{(1 + S_2)^2}{(1 + S_1)} - 1
$$

---

### Duration and Interest Rate Risk

Modified Duration:

$$
\text{ModDur} = \frac{\text{MacDur}}{1 + y}
$$

Price sensitivity:

$$
\frac{\Delta P}{P} \approx -\text{ModDur} \cdot \Delta y
$$

---

### Convexity Adjustment

Second-order approximation:

$$
\frac{\Delta P}{P} \approx -\text{ModDur} \cdot \Delta y + \frac{1}{2} \cdot \text{Convexity} \cdot (\Delta y)^2
$$

---

### Credit Risk Modeling

Expected Loss:

$$
EL = PD \times LGD
$$

Where:
- \( PD \) = Probability of Default  
- \( LGD \) = Loss Given Default  

---

### Securitization

Asset-backed securities redistribute risk through tranching:

- Senior tranche → Low risk, low return  
- Mezzanine tranche → Medium risk, medium return  
- Equity tranche → High risk, high return  

---

## Derivatives

Derivatives derive their value from an underlying asset and are used for hedging, speculation, and arbitrage.

---

### Forward and Futures Pricing

Forward price under no-arbitrage:

$$
F_0(T) = S_0 (1 + r)^T
$$

With cost of carry:

$$
F_0(T) = S_0 e^{(r + c - b)T}
$$

---

### Forward Valuation

Value of a forward contract:

$$
V_t = S_t - F_0(T)(1 + r)^{-(T - t)}
$$

---

### Option Payoffs

Call option payoff:

$$
c_T = \max(0, S_T - X)
$$

Put option payoff:

$$
p_T = \max(0, X - S_T)
$$

---

### Put-Call Parity

Fundamental arbitrage relationship:

$$
c_0 + X(1 + r)^{-T} = S_0 + p_0
$$

---

### Binomial Option Pricing

Risk-neutral probability:

$$
\pi = \frac{1 + r - d}{u - d}
$$

Option valuation:

$$
c_0 = \frac{\pi c^{+} + (1 - \pi)c^{-}}{1 + r}
$$

---

## Key Features

- Structured notes aligned with CFA Level 1 curriculum  
- Strong integration of financial theory and mathematical modeling  
- Emphasis on intuition behind formulas  
- Clean separation of fixed income and derivatives concepts  
- Suitable for both learning and revision  

---

## Applications

- CFA Level 1 exam preparation  
- Fixed income analysis and bond portfolio management  
- Derivatives pricing and risk management  
- Quantitative finance fundamentals  
- Interview preparation for finance and consulting roles  

---

## How to Use

1. Study each concept alongside its mathematical formulation  
2. Focus on relationships between variables  
3. Practice applying formulas to numerical problems  
4. Use this as a revision guide before exams  

---

## Future Improvements

- Addition of solved numerical problems  
- Case-based applications  
- Python/MATLAB implementations  
- Visualization of yield curves and payoff structures  

---

## License

This repository is intended for educational purposes only.

---

## Acknowledgements

This work is based on foundational concepts from the CFA Program curriculum and standard financial theory, including:

- Fixed Income Analysis  
- Derivatives and Risk Management  
- Financial Mathematics  
