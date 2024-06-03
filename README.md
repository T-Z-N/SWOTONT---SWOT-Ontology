# Semantic Modeling of SOFT/SWOT Analysis

This repository contains the ontology and related resources for the paper "Semantic Modeling of SOFT/SWOT Analysis: SOFT/SWOT Ontology and Knowledge Graph" presented at the 6th International Conference on Industry 4.0 and Smart Manufacturing.

## Overview

The SWOT (Strength, Weakness, Opportunity, Threat) analysis is a widely used strategic planning tool. This project addresses the semantic modeling of the initial SOFT (Strength, Opportunity, Fault, Threat)/SWOT analysis to improve its applicability and precision. The primary components include:

- An ontology developed using the Bottom-Up Ontology Development Approach and OWL2.
- A knowledge graph created using the Protege software with synthetic data integration.
- Visualization tools for better understanding and usage of the ontology and knowledge graph.

## Repository Contents

- `ontology/`: Contains the OWL files for the SOFT/SWOT ontology.
- `data/`: Synthetic data used for initializing the knowledge graph.
- `visualizations/`: Visual representations of the ontology and knowledge graph.
- `mapping_rules/`: Mapping rules used in the Cellfie plugin for data integration.
- `examples/`: Example queries and use cases.

## Getting Started

### Prerequisites

- Java (for running Protege)
- [Protege](https://protege.stanford.edu/) (Ontology editor and knowledge management software)
- [Cellfie Plugin](https://github.com/protegeproject/cellfie-plugin) (for data integration)
- [OWL Viz Plugin](https://protegewiki.stanford.edu/wiki/OWLViz) (for ontology visualization)
- [OntoGraf Plugin](https://protegewiki.stanford.edu/wiki/OntoGraf) (for knowledge graph visualization)

### Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/SOFT-SWOT-Ontology.git
    cd SOFT-SWOT-Ontology
    ```

2. **Set up Protege:**
    - Download and install Protege from the official website.
    - Install the Cellfie, OWL Viz, and OntoGraf plugins via Protege's plugin manager.

### Usage

1. **Load the Ontology:**
    - Open Protege.
    - Load the OWL file located in the `ontology/` directory.

2. **Integrate Synthetic Data:**
    - Use the Cellfie plugin to import data from the `data/` directory.
    - Apply the mapping rules found in the `mapping_rules/` directory.

3. **Visualize the Ontology and Knowledge Graph:**
    - Use OWL Viz to visualize the ontology's taxonomy.
    - Use OntoGraf to visualize the relationships and particulars within the knowledge graph.

4. **Query the Knowledge Graph:**
    - Use SPARQL to query the knowledge graph for insights and patterns.
    - Example queries can be found in the `examples/` directory.

## Contributing

We welcome contributions from the community. If you want to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License

This project is licensed under the CC BY-NC-ND license. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or inquiries, please contact the corresponding author:
- **Alican Tüzün** - [Alican.Tuezuen@fh-steyr.at](mailto:Alican.Tuezuen@fh-steyr.at)
