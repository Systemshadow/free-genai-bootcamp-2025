# Requirements, Risks, Assumptions, & Constraints

## Business Requirements
- The company would like to adopt a Pay-As-You-Go (PAYG) model to align infrastructure costs with actual usage.
- Azure is the preferred cloud provider, ensuring compliance with regional regulations by leveraging data storage on EU-based servers.
- The school, located in Bordeaux, France, serves 1,600 students, making an initial infrastructure investment cost-prohibitive.

## Functional Requirements
- Leverage Azure's scalability to accommodate fluctuating student populations and peak usage scenarios.
- Ensure AI services are equipped to handle text translation and NLP with a high degree of accuracy and context-awareness.

## Risks
- Cost Escalation: 
  - PAYG models can lead to unexpected costs during peak usage. Mitigation strategies include leveraging Azure's cost management tools to monitor and control expenses.
- Service Disruptions:
  - High usage during peak times may disrupt performance. Proper scaling strategies and monitoring will be critical to mitigate these risks.

## Assumptions
- Advancements in AI services will result in a decline in operational costs over time.
- The student population remains stable, but the scalable infrastructure will accommodate any future fluctuations.
- Azure's infrastructure and tools will continue to meet regional compliance standards.

## Tooling
- Generative AI (Gen-AI) for:
  - Text translation: Ensuring accurate and context-aware translations.
  - Natural Language Processing (NLP): Enhancing the system's ability to understand and respond to user inputs effectively.

## Constraints
- All data must be stored locally or regionally to comply with data privacy and usage laws, including GDPR in the EU.
- Budgetary constraints necessitate careful monitoring of PAYG expenses, particularly during the initial implementation phase.
