# Advanced Data Structures & Algorithms 2 (DSA2) Repositories

This meta-repository manages all starter (`[assignment]`) and solution (`[assignment]-solution`) repository pairs for the Advanced Data Structures & Algorithms 2 (DSA2) course as Git submodules.

## Managed Sub-repositories

### Labs
- [`dsa2-lab-hello`](dsa2-lab-hello) / [`dsa2-lab-hello-solution`](dsa2-lab-hello-solution): Hello World Environment & Student-Managed Makefile Workflow

### Projects
- [`dsa2-proj-bin-packing`](dsa2-proj-bin-packing) / [`dsa2-proj-bin-packing-solution`](dsa2-proj-bin-packing-solution): Bin Packing Problem Using Approximate Greedy Algorithms
- [`dsa2-proj-lcs`](dsa2-proj-lcs) / [`dsa2-proj-lcs-solution`](dsa2-proj-lcs-solution): Longest Common Subsequence (LCS) Algorithm for Gene Sequence Analysis
- [`dsa2-proj-sorting-analysis`](dsa2-proj-sorting-analysis) / [`dsa2-proj-sorting-analysis-solution`](dsa2-proj-sorting-analysis-solution): Empirical & Runtime Analysis of Insertion Sort and Quicksort
- [`dsa2-proj-tsp-ga`](dsa2-proj-tsp-ga) / [`dsa2-proj-tsp-ga-solution`](dsa2-proj-tsp-ga-solution): Traveling Salesman Problem Solver Using Genetic Algorithm

## Repository Standards

All DSA2 assignments use a `test.mk` testing harness that compiles student code via their custom `Makefile` and checks correctness.

## Usage

To clone this meta-repository along with all course submodules:

```bash
git clone --recurse-submodules https://github.com/uwf-dsa-teaching/dsa2-repos.git
```
