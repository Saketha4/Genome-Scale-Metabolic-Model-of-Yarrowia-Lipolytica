# Genome Scale Metabolic Model of Yarrowia lipolytica

Yarrowia lipolytica is an industrially relevant yeast known for its capabilities in lipid accumulation, organic acid production, and biotechnological applications. This genome-scale metabolic model (GEM) aims to capture the metabolic network of Y. lipolytica to explore its potential in biodiesel production. The goal of this model is to provide a computational tool that enables researchers to simulate and predict the metabolic behavior of Y. lipolytica under various conditions.

[YLModel](https://1drv.ms/x/c/82e11bf00f8ea8cf/Ec-ojg_wG-EggIIlAgAAAAAB6S_4LljsQ-HFR1nG_tWuKQ?e=WXc4de)

## **Model Description** :


This model is designed to represent key metabolic pathways in  Yarrowia lipolytica DSM 3286 with a specific focus on lipid metabolism. It includes pathways relevant to lipid metabolism.

**Objective function** : TAG Biosynthesis

Biological Compartments :
The model includes five compartments to reflect cellular compartmentalization and metabolic flux distribution better:

* Mitochondria (m)
* Cytoplasm (c)
* Endoplasmic Reticulum (r)
* Peroxisome (x) 
* Golgi Apparatus (g)
* Extracellular (e)

### **Reactions and Metabolites** :
The model comprises approximately 353 reactions and  434 metabolites, with gene-protein-reaction associations where available. Major pathways include:

* Central carbon metabolism (glycolysis, TCA cycle, pentose phosphate pathway)
* Oxidative Phosphorylation
* Fatty Acid ( Synthesis, Elongation and Degradation )
* Glycerolipid Pathway
* Glycerophospholipid Pathway
* Sphingolipid Pathway
* Nucleotide metabolism
* Beta-Alanine Metabolism

Data Sources
Tools and Databases: KEGG, BiGG Models, UNIPROT, WoLF PSORT, COBRApy and the Yarrowia lipolytica DSM 3286 genome from NCBI.
Literature: Key studies on Y. lipolytica metabolism and biochemistry.

### **Constraints and Assumptions** :
Objective Function: TAG production is used as the objective function.
Constraints: Oxygen uptake rate and nutrient availability are limited based on typical growth conditions.
Assumptions: All reactions are assumed to follow mass and charge balance, and specific growth media components are defined for simulations.

Model Construction and Curation
The model is built by combining gene annotations and reaction pathways from KEGG database and existing literature on Y. lipolytica. Reactions were added based on KEGG Database. Additionally, stoichiometric consistency checks were performed to correct any imbalances.

Curation Steps
Extracted and validated reactions from the KEGG and BiGG databases.
Incorporated compartment-specific reactions and metabolites.
*Adding reactions to address identified gaps, ensuring connectivity in central metabolic pathways.
Made sure to maintain charge and mass balance.

Simulation Protocols
The model can be used to simulate various metabolic states and environmental conditions using the COBRA Toolbox. Common simulation protocols include:

1. Flux Balance Analysis (FBA): 
2. Gene Knockout Analysis: 
 

**Still working on model curation. Results will be shared here soon.**
### Results and Findings
Preliminary simulations have shown that:

### Limitations and Future Work
Limitations
Some pathways may lack detail due to incomplete genome annotation.\
Model assumptions, such as compartmentalization and reaction constraints, may limit the accuracy of predictions.
Future Work
Refinement of lipid metabolism pathways based on emerging experimental data.\
Incorporation of regulatory elements for more accurate simulations under various conditions.

### References
Publications and data sources such as KEGG, BiGG, and relevant studies on Y. lipolytica metabolism.
