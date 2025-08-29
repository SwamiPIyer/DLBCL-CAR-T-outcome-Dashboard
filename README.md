# DLBCL-CAR-T-outcome-Dashboard
A comprehensive, evidence-based web application for predicting outcomes in patients receiving anti-CD19 CAR-T cell therapy for diffuse large B-cell lymphoma (DLBCL).

## 🚀 Live Demo

[View the Dashboard](https://SwamiPIyer.github.io/cart-outcome-predictor/)

## 📋 Overview

This interactive dashboard provides clinicians and researchers with validated predictive models for CAR-T therapy outcomes in 2L DLBCL based on pre-treatment patient characteristics. The tool synthesizes evidence from landmark clinical trials (ZUMA-1, JULIET, TRANSCEND) and implements published scoring systems to support clinical decision-making.

### Key Features

- **Multi-layered Risk Assessment**: Integrates clinical, laboratory, imaging, and genomic parameters
- **Validated Scoring Systems**: CAR-HEMATOTOX and IPET score calculators
- **Product-Specific Analysis**: Comprehensive toxicity profiles for all three approved products
- **Evidence-Based Predictions**: Outcome probabilities based on published clinical data
- **Interactive Visualizations**: Risk charts and comparative analysis tools

## 🔬 Clinical Foundation

The dashboard is built on the **multi-layered predictive framework** described in current literature:

### Layer 1: Pre-treatment Factors
- Patient demographics (age, ECOG performance status)
- Disease burden (LDH, tumor volume, stage)
- Laboratory markers (inflammatory signature, cytopenias)
- Genomic features (TP53, MYC status, cell of origin)

### Layer 2: CAR-T Product Characteristics
- Axicabtagene ciloleucel (CD28 costimulation)
- Tisagenlecleucel (4-1BB costimulation)  
- Lisocabtagene maraleucel (4-1BB costimulation)

### Layer 3: On-treatment Dynamics
- CAR-T expansion kinetics
- Toxicity development (CRS, ICANS)
- Treatment response patterns

## 🛠️ Technology Stack

- **Frontend**: Pure HTML5, CSS3, JavaScript (ES6+)
- **Charts**: Chart.js for data visualization
- **Icons**: Font Awesome
- **Styling**: Custom CSS with responsive design
- **Deployment**: GitHub Pages compatible

## 📊 Implemented Models

### 1. Comprehensive Risk Assessment
- Weighted scoring system based on clinical evidence
- Risk stratification: Low (0-3), Intermediate (4-7), High (8+)
- Outcome predictions: CR rate, PFS, OS, toxicity risks

### 2. CAR-HEMATOTOX Score
- Predicts severe cytopenias post-CAR-T infusion
- Components: Hemoglobin, platelets, CRP, ferritin
- Validated risk thresholds with clinical implications

### 3. IPET Score
- International Prognostic Index adaptation for CAR-T
- Risk factors: Stage, LDH, absolute neutrophil count
- Prognostic stratification with expected outcomes

### 4. Toxicity Analysis
- Product-specific CRS and ICANS profiles
- ASTCT consensus grading criteria
- Management guidelines by severity grade

## 🏥 Clinical Applications

- **Patient Selection**: Identify optimal CAR-T candidates
- **Risk Stratification**: Predict likelihood of response and toxicity
- **Treatment Planning**: Inform monitoring and management strategies
- **Education**: Teaching tool for CAR-T therapy principles
- **Research**: Hypothesis generation and study design support

## 📁 File Structure

```
cart-outcome-predictor/
│
├── index.html              # Main dashboard application
├── README.md               # Project documentation
├── LICENSE                 # MIT license
│
└── docs/                   # Additional documentation
    ├── clinical-guide.md   # Clinical usage guidelines
    └── validation.md       # Model validation details
```

## 🚀 Getting Started

### Quick Start
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/cart-outcome-predictor.git
   ```

2. Open `index.html` in a modern web browser

3. No additional setup required - runs entirely in the browser

## 📖 Usage Guide

### Risk Assessment Workflow
1. **Input Patient Data**: Enter clinical, laboratory, and imaging parameters
2. **Calculate Risk Score**: Click "Calculate Risk Assessment" to generate predictions
3. **Review Results**: Analyze risk category, outcome probabilities, and contributing factors
4. **Use Specialized Scores**: Apply CAR-HEMATOTOX and IPET models for specific assessments

### Interpreting Results
- **Low Risk (0-3 points)**: 75% CR rate, favorable outcomes expected
- **Intermediate Risk (4-7 points)**: 60% CR rate, moderate toxicity risk
- **High Risk (8+ points)**: 40% CR rate, intensive monitoring required

## 🔬 Evidence Base

### Pivotal Clinical Trials
- **ZUMA-1**: Axicabtagene ciloleucel registration study
- **JULIET**: Tisagenlecleucel long-term follow-up
- **TRANSCEND**: Lisocabtagene maraleucel pivotal trial
- **TRANSFORM**: Second-line randomized study

### Validation Studies
- InflaMix inflammatory biomarker model
- CAR-HEMATOTOX cytopenia prediction
- EASIX/m-EASIX toxicity scores
- Systematic reviews and meta-analyses

## ⚠️ Clinical Disclaimers

- **Educational Purpose**: This tool is for research and educational use only
- **Not for Clinical Decisions**: Clinical management should always involve qualified healthcare providers
- **Individual Variation**: Patient outcomes may vary significantly from model predictions
- **Continuous Updates**: Clinical evidence evolves rapidly; refer to current literature

## 🤝 Contributing

We welcome contributions to improve the dashboard:

1. **Report Issues**: Submit bug reports or feature requests via GitHub Issues
2. **Submit Pull Requests**: Contribute code improvements or new features
3. **Clinical Validation**: Share validation studies or outcome data
4. **Documentation**: Help improve clinical guides and user documentation

### Development Guidelines
- Maintain evidence-based approach
- Cite all clinical sources
- Test across multiple browsers
- Follow accessible design principles
- Document code changes clearly

## 📚 References

Key publications supporting the dashboard models:

1. **Neelapu SS, et al.** Axicabtagene Ciloleucel CAR T-Cell Therapy in Refractory Large B-Cell Lymphoma. *N Engl J Med*. 2017;377(26):2531-2544.

2. **Schuster SJ, et al.** Long-term clinical outcomes of tisagenlecleucel in patients with relapsed or refractory aggressive B-cell lymphomas. *Lancet Oncol*. 2021;22(10):1403-1415.

3. **Abramson JS, et al.** Lisocabtagene maraleucel for patients with relapsed or refractory large B-cell lymphomas. *Lancet*. 2020;396(10254):839-852.

4. **Rejeski K, et al.** CAR-HEMATOTOX: a model for CAR T-cell-related hematologic toxicity. *Blood*. 2021;138(24):2499-2513.

*[Complete reference list available in the dashboard References section]*

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔗 Links

- **Clinical Trials**: [ClinicalTrials.gov](https://clinicaltrials.gov)
- **NCCN Guidelines**: [CAR-T Cell Therapy Guidelines](https://www.nccn.org)
- **ASTCT Consensus**: [Toxicity Grading Criteria](https://www.astct.org)
- **FDA Approvals**: [CAR-T Product Information](https://www.fda.gov)

## 📧 Contact

For questions about clinical applications or model validation:

- **Issues**: [GitHub Issues](https://github.com/SwamiPIyer/cart-outcome-predictor/issues)
- **Discussions**: [GitHub Discussions](https://github.com/SwamiPIyer/cart-outcome-predictor/discussions)

---

**Disclaimer**: This tool is for educational and research purposes only. Clinical decisions should always be made in consultation with qualified healthcare providers and based on individual patient assessment.
