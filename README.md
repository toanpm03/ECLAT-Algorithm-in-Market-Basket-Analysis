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
│   ├── 0. QlikView_2013 invoice detail.xlsx            # detailed invoice in 2013
│   ├── 0. QlikView_2014 invoice detail.xlsx            # detailed invoice in 2014
│   ├── 0. QlikView_Invoice Header.xlsx                 # overall invoice from 2013 to 2014
│   ├── 0. QlikView_Lookup Table.xlsx                   # dimension tables
├── docs/
│   └── data_dictionary.xlsx                            # glossary of data
│   ├── data_model.png                                  # data model
│   └── report.ppt                                      # automated report
│   ├── recommendation.pdf                              # sales analysis
├── notebooks/                     
│   ├── price_optimization.ipynb                        # implementation
└── README.md

