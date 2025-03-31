# **Semantic Modeling of SWOT Analysis**

This repository contains the ontology and related resources for the paper:

**Granular and Relational SWOT Analysis: An Ontological Approach**  
Presented at the *6th International Conference on Industry 4.0 and Smart Manufacturing*.  
[DOI: 10.1016/j.procs.2025.01.317](https://doi.org/10.1016/j.procs.2025.01.317)  

## **Overview**

Traditional Strength, Weakness, Opportunity, and Threat (SWOT) analysis, despite its widespread use, faces a critical limitation in effectively interpreting information through the *SWOT Matrix (SM)*. The conventional matrix lacks the granularity and relational depth necessary for comprehensive decision-making.

To address these shortcomings, this paper introduces **SWOTONT**, an ontology designed to semantically model SWOT analysis. SWOTONT is developed using a bottom-up ontology development approach, incorporating insights from a literature review and domain experts. The ontology enhances SWOT analysis by introducing finer subcategories, defining interrelationships among factors, and structuring the information for improved knowledge extraction.

By leveraging **OWL2**, SWOTONT provides a structured, semantic foundation for strategic decision-making. Future research will focus on empirical validation through case studies, integrating an upper ontology, and exploring further applications of the model.

## **Key Features**
- **Ontology-driven SWOT Analysis:** Developed using the **Bottom-Up Ontology Development Approach** and **OWL2**.
- **Granular SWOT Categorization:** Enhanced classification of SWOT factors with subcategories and detailed attributes.
- **Relational Context:** Captures influence patterns between SWOT elements for better strategic analysis.

## **Repository Contents**
- `ontology/` – Contains the **OWL** files for SWOTONT.

## **Getting Started**

### **Prerequisites**
- **Java** (for running Protégé)
- [**Protégé**](https://protege.stanford.edu/) (Ontology editor and knowledge management tool)

### **Installation**

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/SWOTONT.git
    cd SWOTONT
    ```

2. **Set up Protégé:**
    - Download and install Protégé from the official website.
    - Install **Cellfie, OWL Viz,** and **OntoGraf** plugins via Protégé’s plugin manager.

### **Usage**

**Load the Ontology:**
- Open Protégé.
- Load the **OWL** file from the `ontology/` directory.

## **Contributing**

Contributions are welcome! If you’d like to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to your branch (`git push origin feature-branch`).
5. Open a **Pull Request**.

## **License**

This project is licensed under the **CC BY-NC-ND** license. See the [LICENSE](LICENSE) file for details.

## **Contact**

For inquiries, please contact:  
📧 **Alican Tüzün** – [Alican.Tuezuen@fh-steyr.at](mailto:Alican.Tuezuen@fh-steyr.at)
