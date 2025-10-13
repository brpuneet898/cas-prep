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
