# A Modular Strategy to Build a Large-Scale Functional Status Knowledge Graph

**Authors:** Mauro Dragoni, Tania Bailoni, Gabriele Sacco and Loris Bozzato

## Abstract
* The issue statement for the effective care of people with chronic diseases, multi-morbidity, impairments, and an aging population is presented clearly in the abstract. The importance of Functional Status Information (FSI) data is emphasized, and personal knowledge graphs (PKGs) are suggested as a method for organizing and analyzing FSI data. The modular design of FuS-KG, intended to improve scalability, management, understandability, and reuse, is highlighted.
* It does not, however, contain any discussion of findings or outcomes, background information on current approaches, or detailed information on procedures and techniques. Furthermore, the narrow keyword selection might not include all pertinent information.

## Introduction 
* The difficulty of ontology modularization and its significance for creating high-quality ontologies are both clearly highlighted in the introduction. In it, a modular personal knowledge graph called FuS-KG for describing functional status information (FSI) is introduced. It does this by referencing the authors' prior work on a virtual coach solution and the underlying ontology. 
* The concepts of scalability, complexity management, understandability, and reuse are covered, with a focus on their significance in directing the FuS-KG modular strategy. 
* However, the introduction may have been improved by adding background information on ontology engineering processes, providing more information about the virtual coach solution, and presenting particular evaluation outcomes.

## Related Work
* Understanding functional status and the difficulties in managing health with little healthcare resources are clearly justified in this section. It states the paper's limitations in terms of giving a survey of FSI approaches, but it also points interested readers towards other resources for more details.
* The section provides a succinct overview of popular ontology modularity approaches, emphasizing their impact on the creation of FuS-KG modules. 
* It might benefit from specific references or citations to help with further research investigation as it lacks in-depth analysis and comparisons of different approaches.

## FuS-KG Modules
* Food Module:
Strengths: Categorizes and provides detailed information about basic foods and recipes. Enables precise tracking of users' dietary intake.
Weaknesses: Limited number of food instances. 
* Activity Module:
Strengths: Defines various physical activity categories. Provides energy cost measurements. Allows differentiation between light, moderate, and vigorous activities.
Weaknesses: List of physical activities may not cover all possible activities. Energy cost measurements may not be accurate for every individual.
* Monitoring Module:
Strengths: Enables monitoring of users' behaviors. Defines rules and violations for adherence to health goals. Provides structured representations for data analysis and advice generation.
Weaknesses: Effectiveness relies on accuracy and completeness of user data. 
* User Module:
Strengths: Represents user information, consumed foods, and performed activities. Associates violations with users, allowing personalized feedback and recommendations.
Weaknesses: Relies on user-provided information, which may be subjective or incomplete. May require additional data validation mechanisms.
* Enablers Module:
Strengths: Supports behavior change processes. Defines interventions, treatments, strategies, and techniques. Allows customization based on behavior change goals.
Weaknesses: Effectiveness of interventions may vary among individuals. May not cover all possible intervention approaches.
* Barriers Module:
Strengths: Classifies barriers related to behavior change. Considers various factors. Enables reasoning based on medical knowledge.
Weaknesses: Effectiveness relies on accuracy and availability of barrier classifications and associated medical knowledge.
* Arguments Module:
Strengths: Supports persuasive dialogues for motivating behavior change. Provides various argument types and topics. Helps address beliefs and concerns related to healthcare issues.
Weaknesses: Persuasiveness of arguments may vary among individuals and depending on how good of a dialog can be formed, the effectiveness might be impacted.

## Empirical Evaluation
Strengths:

* Accuracy: FuS-KG was judged satisfactory in terms of accuracy and correctness.
* Adaptability: FuS-KG can be extended and specialized without requiring axiom removal.
* Clarity: Clear communication through concept labels, definitions, and descriptions.
* Completeness: FuS-KG was deemed complete, covering necessary information for a healthy lifestyle.
* Computational Efficiency: Reasoning within FuS-KG completed in a reasonable time frame.
Conciseness, Consistency, and Coherence: Relevant and non-redundant axioms, with no contradictions.
* Organizational Fitness: FuS-KG deployed as a web service, suitable methodology adopted.

Weaknesses:
* Adaptability: Non-monotonic updates of user profiles when associated with new profiles.
* Completeness: A need to include commercial product individuals for improved user engagement.
* OOPS! Evaluation: Some pitfalls related to reused ontologies, but resolved for newly implemented entities.


## Conclusions
The FuS-KG modules have several strengths that contribute to enhancing the AI capabilities of coaching systems, such as providing a solid foundation for monitoring users' functional status. The future expansion of the knowledge base through collaboration with domain experts and data mining techniques demonstrates a commitment to keeping the ontology comprehensive and up-to-date. Additionally, the integration of natural language understanding (NLU) and natural language generation (NLG) components holds the potential to transform natural language texts into semantic representations and generate meaningful contextual feedback. However, some weaknesses should be addressed, including the need for constant updates to the knowledge base, the complexity of integrating NLU and NLG components, and the lack of a living lab evaluation to fully assess the effectiveness and performance of the FuS-KG modules in real-world scenarios.




