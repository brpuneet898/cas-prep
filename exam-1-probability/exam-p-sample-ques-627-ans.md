# Solutions to Sample Questions 627-Set

## **Solution 1**

Let:

- G = watched gymnastics = 28%
- B = watched baseball = 29%
- S = watched soccer = 19%
- G ∩ B = 14%
- B ∩ S = 12%
- G ∩ S = 10%
- G ∩ B ∩ S = 8%

We use the inclusion-exclusion principle:

$$
P(G ∪ B ∪ S) = P(G) + P(B) + P(S) - [P(G ∩ B) + P(B ∩ S) + P(G ∩ S)] + P(G ∩ B ∩ S)
$$

$$
P(G ∪ B ∪ S) = 28 + 29 + 19 - (14 + 12 + 10) + 8 = 48
$$

So, **48% watched at least one** of the sports.

Hence, **none watched = 100% - 48% = 52%**.

### Answer: (D) 52%

---

## **Solution 2**

Let:

- $ P(\text{neither}) = 0.35 $
- So, $ P(\text{at least one}) = 0.65 $
- Of those coming to the PCP:
  - $ P(\text{referred to specialist}) = 0.30 $
  - $ P(\text{lab work}) = 0.40 $
  
We are to find $ P(\text{both}) $.

By inclusion-exclusion:
$$
P(\text{lab or specialist}) = P(\text{lab}) + P(\text{specialist}) - P(\text{both})
$$
We know $$ P(\text{lab or specialist}) = 0.65 $$

Hence:
$$
0.65 = 0.40 + 0.30 - P(\text{both})
$$
$$
P(\text{both}) = 0.70 - 0.65 = 0.05
$$

### Answer: (A) 0.05

---

## **Solution 3**

Given:
$$
P(A ∪ B) = 0.7, \quad P(A ∪ B') = 0.9
$$
We use:
$$
P(A ∪ B') = P(A) + P(B') - P(A ∩ B')
$$
But note:
$$
P(B') = 1 - P(B)
$$

We can write:
$$
P(A ∪ B) = P(A) + P(B) - P(A ∩ B)
$$

Also,
$$
P(A ∪ B') = P(A) + 1 - P(B) - P(A ∩ B')
$$

Since $ P(A ∩ B) + P(A ∩ B') = P(A) $, we can find:

$$
P(A ∪ B) + P(A ∪ B') = [P(A) + P(B) - P(A ∩ B)] + [P(A) + 1 - P(B) - P(A ∩ B')]
$$
Simplify:
$$
= 2P(A) + 1 - [P(A ∩ B) + P(A ∩ B')]
$$
$$
= 2P(A) + 1 - P(A)
$$
$$
= 1 + P(A)
$$

Hence:
$$
P(A) = P(A ∪ B) + P(A ∪ B') - 1 = 0.7 + 0.9 - 1 = 0.6
$$

### Answer: (D) 0.6

---

## **Solution 4**

Let:

- Urn 1: 4 red, 6 blue → $P(\text{red})=\frac{4}{10}=0.4$, $P(\text{blue})=0.6$
- Urn 2: 16 red, $x$ blue → total $16+x$
  - $P(\text{red})=\frac{16}{16+x}$
  - $P(\text{blue})=\frac{x}{16+x}$

Same-color probability:
$$
0.44 = 0.4\cdot\frac{16}{16+x} + 0.6\cdot\frac{x}{16+x}
$$
Multiply by $(16+x)$:
$$
0.44(16+x) = 0.4\cdot16 + 0.6x = 6.4 + 0.6x
$$
Expand and solve:
$$
7.04 + 0.44x = 6.4 + 0.6x
\Rightarrow 7.04 - 6.4 = 0.6x - 0.44x
\Rightarrow 0.64 = 0.16x
\Rightarrow x = \frac{0.64}{0.16} = 4
$$

### Answer: (A) 4

---

## **Solution 5**

Given:

- Total $=10000$, Young $=3000$, Male $=4600$, Married $=7000$
- Young males $=1320$, Married males $=3010$, Young married persons $=1400$, Young married males $=600$

Young married females:
$$
1400-600=800
$$

Young females total:
$$
3000-1320=1680
$$

Young, female, single:
$$
1680-800=880
$$

### Answer: (D) 880

---

## **Solution 6**

Data:

- Total men $=937$
- Heart-disease deaths $=210$
- Men with $\ge 1$ parent with heart disease $=312$, of whom $102$ died of heart disease

Men with **no** parental heart disease:
$$
937-312=625
$$

Heart-disease deaths with **no** parental history:
$$
210-102=108
$$

Required probability:
$$
P(\text{HD death}\mid \text{no parental HD})=\frac{108}{625}=0.1728
$$

### Answer: (B) 0.173

---

## **Solution 7**

Group proportions:

- Only auto: $65\%-15\% = 50\%$
- Only homeowners: $50\%-15\% = 35\%$
- Both: $15\%$

Renewal probabilities (company estimates):

- Only auto $\rightarrow 40\%$
- Only homeowners $\rightarrow 60\%$
- Both $\rightarrow 80\%$ (renew at least one)

Total renewing at least one policy:
$$
0.50\cdot 0.40\;+\;0.35\cdot 0.60\;+\;0.15\cdot 0.80
=0.20+0.21+0.12=0.53
$$

### Answer: (D) 53%

---

## **Solution 8**

Let $p=P(\text{physical therapist})$, $c=P(\text{chiropractor})$.
Given $P(\text{both})=0.22$, $P(\text{neither})=0.12$, and $c=p+0.14$.

By inclusion–exclusion:
$$
P(\text{PT}\cup \text{Chiro})=p+c-0.22=1-0.12=0.88
\Rightarrow p+c=1.10
$$
Using $c=p+0.14$:
$$
p+(p+0.14)=1.10 \;\Rightarrow\; 2p=0.96 \;\Rightarrow\; p=0.48
$$

### Answer: (D) 0.48

---

## **Solution 9**

Let $A$ = “insures exactly one car”, $B$ = “insures more than one car”, $S$ = “insures a sports car”.

Given: $P(B)=0.70 \Rightarrow P(A)=0.30$, $P(S)=0.20$, and $P(S\mid B)=0.15$.

By total probability,
$$
P(S)=P(S\mid A)P(A)+P(S\mid B)P(B)
\Rightarrow 0.20=P(S\mid A)\cdot 0.30+0.15\cdot 0.70.
$$
Hence
$$
P(S\mid A)=\frac{0.20-0.105}{0.30}=\frac{0.095}{0.30}=\frac{19}{60}.
$$
Therefore
$$
P(A\cap S^c)=P(A)\,[1-P(S\mid A)]=0.30\left(1-\frac{19}{60}\right)
=0.30\cdot\frac{41}{60}=0.205\approx 0.21.
$$

### Answer: (B) 0.21

---

## **Solution 10**

Let $C$ = collision, $D$ = disability.
Given: $P(C)=2P(D)$, $C$ and $D$ independent, and $P(C\cap D)=0.15$.

With independence,
$$
P(C\cap D)=P(C)P(D)=0.15,\quad P(C)=2P(D)=2d.
$$
So
$$
(2d)\,d=0.15\;\Rightarrow\;2d^2=0.15\;\Rightarrow\;d=\sqrt{0.075}\approx 0.2739,\quad
c=2d\approx 0.5477.
$$
Probability of neither:
$$
P(C^c\cap D^c)=(1-c)(1-d)=1-(c+d-cd)
=1-(0.5477+0.2739-0.15)\approx 0.3284\approx 0.33.
$$

### Answer: (B) 0.33

---
