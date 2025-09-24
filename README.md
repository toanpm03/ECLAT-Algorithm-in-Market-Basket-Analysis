## Application of the ECLAT Algorithm in Market Basket Analysis
- Author: Toan Pham Minh, Binh Nguyen To, Dat Mai Hien, Tram Nguyen Hong
  
- Project Type: Association rule mining

- Tech Stack: Python
### Objective
- Definition & Core Idea: ECLAT (Equivalence Class Clustering and bottom-up Lattice Traversal) mines frequent itemsets using a vertical database format.

- Comparison with Apriori: Evaluated across criteria such as efficiency, memory usage, and scalability.
  
- Algorithm Design & Workflow: Class structure, recursive depth-first search, and TID-set intersections.
  
- Practical Applications: Market Basket Analysis → frequent itemset discovery & association rule mining → optimize product placement, inventory management, and personalized recommendations.
### Project Structure
```text
├── data/
│   ├── source.csv             # Transaction data in 2015
├── docs/
│   └── presentation.ppt       # Summary of report
│   ├── report.pdf             # Detailed report
├── notebooks/                     
│   ├── source_code.ipynb      # implementation
└── README.md
