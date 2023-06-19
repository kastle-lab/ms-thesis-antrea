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
Comments regarding weaknesses of the following metrics:

* Accuracy: Limited information regarding the real world representation.
* Clarity: Even though it is stated that every definition is well documented for the intented users, there is no information about any feedback for them to validate it.
* Completeness : Even though the evaluators aggreed on the completeness of the  FuS-KG, there was nothing mentioned regarding potential risks or issues that might occur.
* Consistency: Even though the evaluators stated that they observed little bias between the documentation containing the informal description of the concepts and their formalization, more details are lacking.
* Organizational fitness : Feedback from users was not clearly stated on wherether the site is as easily as accessible as mentioned.
* OOPS! tool evaluation: Even thought the stated issues are said to be resolved, details regarding "how" are missing.


## Conclusions
* Overall, the paper provides several strengths that contribute to enhancing the AI capabilities of coaching systems, such as providing a solid foundation for monitoring users' functional status.
* The future expansion of the knowledge base through collaboration with domain experts and data mining techniques demonstrates a commitment to keeping the ontology comprehensive and up-to-date.
* However, more details could be addressed regarding the need for constant updates to the knowledge base along with the complexity of integrating NLU and NLG components.
* Also, more detals could be stated regarding the lack of a living lab evaluation to fully assess the effectiveness and performance of the FuS-KG modules in real-world situations.
* Finally, more details should be present regarding the empirical evaluation, providing more insight regarding feedback from the users and issue resolution.


