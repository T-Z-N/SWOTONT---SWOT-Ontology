# Semantic Modeling of SWOT Analysis

This repository contains the ontology and related resources for the paper "Granular and Relational SWOT Analysis: An Ontological Approach" presented at the 6th International Conference on Industry 4.0 and Smart Manufacturing.

## Overview

The traditional Strength, Weakness, Opportunity, and Threat (SWOT) analysis, despite its popularity [30], faces a significant challange
in interpreting information through the ”SWOT Matrix (SM)”[14]. The conventional matrix inherently fails to capture the
complexity and detailed charecteristics neccesary for comprehensive decision-making. Therefore this paper introduces an innovative
approach to address these limitations by an ontology SWOTONT [38] representing the domain of SWOT analysis. SWOTONT
is developed through a literature review and a bottom-up ontology development approach [17] providing context to the SWOT attributes
by introducing finer subcategories and mapping their interrelationships. By developing a structured semantic approach,
authors aimed to enable more precise knowledge extraction and support advanced strategic analysis. Future work will focus on
empirical validation through case studies and domain expert feedback, integrating an upper ontology and exploring additional
applications of the model.

- An ontology developed using the Bottom-Up Ontology Development Approach and OWL2.

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
