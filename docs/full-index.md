# Full index

<!-- collana-organizzazione -->
## How to use these notes

- **Website and PDF.** Each chapter of the website is a chapter of the lecture notes, with the same numbers and the same colors; long chapters are split into one page per section.
- **At the top of each chapter** a bar with the part, the PDF of the lecture notes, the slides, the exercises and the apps of the chapter; at the bottom, the link to the exercises.
- **The problems.** The definition of each problem is on its page of the course [Combinatorial Optimization](https://fabiofurini.github.io/combinatorial-optimization/): each chapter starts with the link.

The boxes have the same colors as in the lecture notes:

<div class="grid" markdown>

!!! definizione "Definition"
    The precise meaning of a new concept.

!!! teorema "Theorem, proposition, observation"
    A result to remember, with its hypotheses.

!!! esempio "Example"
    A computation worked out in full, one step at a time.

!!! formula "Formula"
    In pink the formulas to keep at hand: the recurrences of dynamic programming.

!!! algoritmo "Algorithm"
    The pseudo-code, step by step as in the lecture notes.

!!! chiave ""
    **In green** the key point to take away.

</div>

??? dimostrazione "Proof: opens with a click"
    All proofs are included, but folded: first read the statement, then open the proof when you want to study it. The same holds for the solutions of the exercises.
<!-- /collana-organizzazione -->

All the pages of the website, in the order of the menu: the chapters with their sections and the other pages.

## [Principles](principles.md)

- **[1. Principles of dynamic programming](dp-principles/index.md)** · [Exercises](exercises/dp-principles.md)
    - [1.1 Divide, conquer and combine](dp-principles/index.md#11-divide-conquer-and-combine)
    - [1.2 Problem properties required by DP algorithms](dp-principles/index.md#sez-sec-dp-properties)
    - [1.3 Steps for designing a DP algorithm](dp-principles/index.md#13-steps-for-designing-a-dp-algorithm)
    - [1.4 The DP algorithms of this module](dp-principles/index.md#14-the-dp-algorithms-of-this-module)
    - [1.5 Typical mistakes](dp-principles/index.md#15-typical-mistakes)
    - [1.6 In summary](dp-principles/index.md#16-in-summary)

## [Knapsack problems](knapsack-problems.md)

- **[2. DP for the 0/1 knapsack problem](dp-knapsack/index.md)** · [Exercises](exercises/dp-knapsack.md)
    - [2.1 Instances and feasible solutions](dp-knapsack/index.md#21-instances-and-feasible-solutions)
    - [2.2 A first DP algorithm](dp-knapsack/a-first-dp-algorithm.md)
    - [2.3 A second DP algorithm](dp-knapsack/a-second-dp-algorithm.md)
    - [2.4 Typical mistakes](dp-knapsack/typical-mistakes.md#24-typical-mistakes)
    - [2.5 In summary](dp-knapsack/typical-mistakes.md#25-in-summary)
- **[3. DP for the unbounded knapsack problem](dp-unbounded-knapsack/index.md)** · [Exercises](exercises/dp-unbounded-knapsack.md)
    - [3.1 Instances and feasible solutions](dp-unbounded-knapsack/index.md#31-instances-and-feasible-solutions)
    - [3.2 A first DP algorithm](dp-unbounded-knapsack/a-first-dp-algorithm.md)
    - [3.3 A second DP algorithm](dp-unbounded-knapsack/a-second-dp-algorithm.md)
    - [3.4 Typical mistakes](dp-unbounded-knapsack/typical-mistakes.md#34-typical-mistakes)
    - [3.5 In summary](dp-unbounded-knapsack/typical-mistakes.md#35-in-summary)
- **[4. DP for the bounded knapsack problem](dp-bounded-knapsack/index.md)** · [Exercises](exercises/dp-bounded-knapsack.md)
    - [4.1 Instances and feasible solutions](dp-bounded-knapsack/index.md#41-instances-and-feasible-solutions)
    - [4.2 A DP algorithm](dp-bounded-knapsack/index.md#42-a-dp-algorithm)
    - [4.3 Typical mistakes](dp-bounded-knapsack/index.md#43-typical-mistakes)
    - [4.4 In summary](dp-bounded-knapsack/index.md#44-in-summary)
- **[5. DP for the subset sum problem](dp-subset-sum/index.md)** · [Exercises](exercises/dp-subset-sum.md)
    - [5.1 A DP algorithm](dp-subset-sum/index.md#51-a-dp-algorithm)
    - [5.2 Typical mistakes](dp-subset-sum/index.md#52-typical-mistakes)
    - [5.3 In summary](dp-subset-sum/index.md#53-in-summary)
- **[6. DP for the multiple-choice knapsack problem](dp-multiple-choice-knapsack/index.md)** · [Exercises](exercises/dp-multiple-choice-knapsack.md)
    - [6.1 A DP algorithm](dp-multiple-choice-knapsack/index.md#61-a-dp-algorithm)
    - [6.2 Typical mistakes](dp-multiple-choice-knapsack/index.md#62-typical-mistakes)
    - [6.3 In summary](dp-multiple-choice-knapsack/index.md#63-in-summary)
- **[7. DP for the multidimensional knapsack problem](dp-multidimensional-knapsack/index.md)** · [Exercises](exercises/dp-multidimensional-knapsack.md)
    - [7.1 A DP algorithm](dp-multidimensional-knapsack/index.md#71-a-dp-algorithm)
    - [7.2 Typical mistakes](dp-multidimensional-knapsack/index.md#72-typical-mistakes)
    - [7.3 In summary](dp-multidimensional-knapsack/index.md#73-in-summary)
- **[8. DP for the knapsack problem with setups](dp-knapsack-setups/index.md)** · [Exercises](exercises/dp-knapsack-setups.md)
    - [8.1 A DP algorithm](dp-knapsack-setups/index.md#81-a-dp-algorithm)
    - [8.2 Typical mistakes](dp-knapsack-setups/index.md#82-typical-mistakes)
    - [8.3 In summary](dp-knapsack-setups/index.md#83-in-summary)
- **[9. DP for the multiple knapsack problem](dp-multiple-knapsack/index.md)** · [Exercises](exercises/dp-multiple-knapsack.md)
    - [9.1 A DP algorithm](dp-multiple-knapsack/index.md#91-a-dp-algorithm)
    - [9.2 Typical mistakes](dp-multiple-knapsack/index.md#92-typical-mistakes)
    - [9.3 In summary](dp-multiple-knapsack/index.md#93-in-summary)

## [Lot sizing problems](lot-sizing-problems.md)

- **[10. DP for the uncapacitated lot sizing problem](dp-lot-sizing/index.md)** · [Exercises](exercises/dp-lot-sizing.md)
    - [10.1 Notation, model and feasible solutions](dp-lot-sizing/index.md#101-notation-model-and-feasible-solutions)
    - [10.2 A DP algorithm for the ULS](dp-lot-sizing/a-dp-algorithm-for-the-uls.md)
    - [10.3 Typical mistakes](dp-lot-sizing/typical-mistakes.md#103-typical-mistakes)
    - [10.4 In summary](dp-lot-sizing/typical-mistakes.md#104-in-summary)
- **[11. DP for the capacitated lot sizing problem](dp-capacitated-lot-sizing/index.md)** · [Exercises](exercises/dp-capacitated-lot-sizing.md)
    - [11.1 Notation, model and feasible solutions](dp-capacitated-lot-sizing/index.md#111-notation-model-and-feasible-solutions)
    - [11.2 A DP algorithm for the CLS](dp-capacitated-lot-sizing/index.md#112-a-dp-algorithm-for-the-cls)
    - [11.3 Typical mistakes](dp-capacitated-lot-sizing/index.md#113-typical-mistakes)
    - [11.4 In summary](dp-capacitated-lot-sizing/index.md#114-in-summary)

## [Miscellaneous problems](miscellaneous-problems.md)

- **[12. DP for the coin change problem](dp-coin-change/index.md)** · [Exercises](exercises/dp-coin-change.md)
    - [12.1 Instances and feasible solutions](dp-coin-change/index.md#121-instances-and-feasible-solutions)
    - [12.2 A DP algorithm](dp-coin-change/index.md#122-a-dp-algorithm)
    - [12.3 Typical mistakes](dp-coin-change/index.md#123-typical-mistakes)
    - [12.4 In summary](dp-coin-change/index.md#124-in-summary)
- **[13. DP for the rod cutting problem](dp-rod-cutting/index.md)** · [Exercises](exercises/dp-rod-cutting.md)
    - [13.1 Instances and feasible solutions](dp-rod-cutting/index.md#131-instances-and-feasible-solutions)
    - [13.2 A first DP algorithm](dp-rod-cutting/a-first-dp-algorithm.md)
    - [13.3 A second DP algorithm](dp-rod-cutting/a-second-dp-algorithm.md)
    - [13.4 Typical mistakes](dp-rod-cutting/typical-mistakes.md#134-typical-mistakes)
    - [13.5 In summary](dp-rod-cutting/typical-mistakes.md#135-in-summary)

## Other pages

- [Exercises](exercises/index.md)
- [Lab](lab/index.md)
- [Downloads](downloads.md)
- [Self-assessment](self-assessment.md)
