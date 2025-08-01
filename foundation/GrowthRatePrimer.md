## Growth rates

Growth comes in tiers, each one a qualitative leap in “how quickly quick” really is.
1. **Linear** growth adds a fixed amount every step; your car cruises on cruise-control at 60 mph.
2. **Exponential** growth multiplies by a fixed factor; compound interest or a virus that doubles every week.
3. **Super-exponential** growth multiplies by a factor that itself skyrockets; a chain of 3-D printers that build more printers, each generation cranking machines out faster than the last. The key intuition is **doubling time**: it stays constant for exponential curves but shrinks for super-exponential ones.

| Growth type       | Canonical form _f(t)_ | What the rate _f′(t)_ does               | Doubling time trend                           | Everyday analogy               |
| ----------------- | --------------------- | ---------------------------------------- | --------------------------------------------- | ------------------------------ |
| Linear            | _k t + c_             | Constant slope _k_                       | Doubles only if you wait **twice as long**    | $10 added to savings every day |
| Exponential       | _a b^t_ (b > 1)       | Proportional to current size (_f′ ∝ f_)  | **Constant** (e.g., every 7 days)             | 7% annual compound interest    |
| Super-exponential | e.g. _b^{c^t}_, _t!_  | Rate itself accelerates faster than size | **Shrinks** each round (7 days → 3.5 → 1.7 …) | Printer-makes-printer cascade  |
