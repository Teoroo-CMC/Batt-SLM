This repository implements a unified generative–predictive framework for molecular design, combining generative AI, redox property prediction, and chemical–protein interaction (CPI) modeling to enable multi-objective molecular optimization.
We target applications in electrochemical energy storage materials and molecular bioactivity screening.

.
├── Batt-SLM/                # generator input molecules
│   ├── molecules.smi        
│   └── ...
│
├── redox_predictor/         # 
│   ├── models/
│   ├── data/
│   ├── train.py
│   ├── inference.py
│   └── README.md
│
├── cpi_predictor/           # Chemical-Protein Interaction (CPI)
│   ├── models/
│   ├── data/
│   ├── train.py
│   ├── inference.py
│   └── README.md
├── results/                 
└── README.md
