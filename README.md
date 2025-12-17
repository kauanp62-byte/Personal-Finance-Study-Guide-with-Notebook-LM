# Personal-Finance-Study-Guide-with-Notebook-LM
This project demonstrates the use of Google's NotebookLM as an AI-powered learning assistant to create an interactive study guide on introductory personal finance. By curating and synthesizing multiple open-source financial documents, this notebook provides structured learning materials, strategic prompts, and critical analysis tools.

# Learning Objectives
1. Understand core persona finance principles through active AI-assisted learning.
2. Create reusable study materials and prompts for ongoing education.
3. Practice source synthesis across multiple authoritative documents.
4. Develop critical thinking skills for evaluating financial information.

# Source Documents
|Document|Source| Year of Publication |
|--------|-------|--------------------|
|TOP Análise de Investimentos| GOV BR | 2025 |
|TOP Planejamento Financeiro Pessoal | GOV BR| 2025 |
|TOP Mercado de Valores Mobiliários Brasileiros| GOV BR| 2024 |


All documents are publicy available government educational resources.


## How to Use This Repository
### For Learners
Study the exported materials in notebook_export/
Practice with the case studies in case_studies/
Use the prompt library to create your own learning materials

### For Educators
Adapt the structure for different subjects
Use the methodology for teaching source evaluation
Implement the assessment tools in your courses

### For Developers
Examine the prompt engineering approaches
Study the knowledge organization strategies
Apply similar structures to other AI learning tools


# NotebookLM Features Implemented

## 1. Source Synthesis Engine
   a. Citation tracking for all generated content.  b. Identification of consensus vs. contradictory advice.

## 2. Interactive Learning Modules
### Module 1.
Budgeting methods comparison
Emergency fund strategies
Debt management approaches

### Module 2.
Risk-return tradeoff analysis
Portfolio diversification examples
Compound interest calculators

### Module 3.
Retirement savings scenarios
Age-based strategy comparison
Tax-advantaged accounts guide

## 3. Prompt Engineering Showcase
I developed and tested multiple prompt strategies.
### Extraction Prompts:
"Extract all definitions of 'compound interest' from the documents and compare their explanations"

### Analysis Prompts:
"Analyze the advice about credit card usage across all three sources. What patterns emerge? Are there conflicting recommendations?"

### Application Prompts:
"Design a 12-month financial improvement plan for a recent college graduate  earning R$45,000/year with R$25,000 in student loans, using principles from the three source documents."

### Evaluation Prompts:
"Critically evaluate the assumptions made in these government guides. 
What economic perspectives might be underrepresented?"

## Sample Outputs
### Glossary Entry
#### Prompt: "Analyze the advice about credit card usage across all three sources. What patterns emerge? Are there conflicting recommendations?"

#### Output: "The analysis of the provided sources (which include materials on Personal Financial Planning, Investment Analysis, and the Securities Market) reveals a fairly consistent pattern of advice regarding the use of credit cards in the context of personal finance.

The documents covering Personal Financial Management identify the credit card not as a cash flow management tool, but primarily as a high-cost, high-risk form of revolving credit, recommending its exclusion from consumption financing.

Patterns of Advice on Credit Card Use
Three main patterns emerge from the sources regarding credit cards and revolving credit:

1. High Cost and Extreme Risk
The primary pattern is the discouragement of using credit cards for debt due to their prohibitive cost and high risk.
• Revolving credit (which includes overdraft protection and credit cards) is classified as the most expensive credit and should be avoided.
• The interest rates charged in the market for revolving credit are higher than those for other credit modalities due to its high risk for the financial institution (being an unsecured loan, without a maturity date or pre-established payment conditions).

2. Consumption Financing Should Be Avoided
The sources strongly advise against using credit cards to finance consumption expenses, as this compromises future income.
• Financing the credit card bill or making installment purchases (retail credit) are considered traps that should be "crossed off the map," and the individual should pay for consumption expenses with available cash.
• The recommendation is clear: Acquire the habit of saving and paying cash. The use of credit should be reserved only for acquiring assets that build wealth, such as real estate financing.

3. Connection with Behavioral Biases
Credit card use is directly linked to behavioral biases that harm an individual's financial health.
• Present Bias (or Hyperbolic Discounting) is identified as a tendency that leads people to take on more debt by excessively prioritizing immediate reward.
• The mind tends to create the illusion that purchasing power is greater than it actually is.
• To combat this bias and the illusion of greater purchasing power, it is recommended to reduce the credit limit and decrease credit card usage.

Conflicting Recommendations
There are no conflicting recommendations about credit card use in the examined documents. The texts are unanimous in positioning revolving credit as an expensive and dangerous choice that should be avoided in personal financial planning, with the goal of reducing debt and increasing savings capacity.

The Investment Analysis documents (such as "TOP-Analise-de-Investimentos.pdf") and the material on the Securities Market ("TOP-Mercado-de-Valores-Mobiliarios-Brasileiro.pdf") focus on assets, capital markets, and corporate governance and, therefore, do not contain direct advice on personal finances or the use of credit cards."


### Comparative Analysis Table:
|Topic|Relevant Information|Source Document(s)|
|------|-------------------|------------------|
|Emergency Fund Size | The Emergency Fund is a financial reserve for unforeseen events and should range between three to six months of an individual's or family's current expenses. It is recommended that this reserve be at least three times the monthly budget. The solidity of this reserve can be measured by the "Monthly Expense Coverage Ratio," calculated by dividing short-term assets by monthly expenses. | All documents|
|First Investment|The primary savings goal (and therefore the first investment) should be the Financial Reserve for emergencies. For this purpose, the investment should prioritize liquidity and safety (low risk) over yield. Post-fixed, low-volatility investments with daily liquidity are the most suitable. Recommended examples include Tesouro Selic (Brazilian Treasury bonds linked to the SELIC rate), CDB DI (Bank Deposit Certificates linked to the interbank deposit rate), and Referenced DI Funds.| All documents |
|Credit Utilization| Revolving credit, including overdraft and credit cards, is the most expensive credit and should be avoided, as it compromises future income. Credit should only be used for acquiring assets that build wealth (such as real estate financing) and not for financing consumption expenses. The Debt-to-Income Ratio (Monthly debt amount / Net monthly income) should be kept below 30% to ensure payment capacity and financial health. | All documents |


# Getting Started
## Prerequisites
1. Google Account for NotebookLM access
2. Basic understanding of personal finance concepts
3. Critical thinking mindset for source evaluation

## Setup Instructions:
1. Clone this repository
2. Acess NotebookLM:
   Visit NotebookLM Google
   Create a new notebook titled "Personal Finance Study Guide"
3. Upload Source Documents:
   Navigate to source_documents folder
   Upload all 3 PDFs to NotebookLM
   Allow time for processing and source analysis
4. Recreate the Study Structure
   Import prompts from __notebook_export/prompts_library.md__
   Follow the module progression in __structured_study_guide.md__
   Test prompts with different variations

## Quick Start Prompts:
Begin with these starter prompts in NotebookLM:

### Starter Prompt 1: Overview
"Create a master outline of personal finance topics covered across all five documents, organized from basic to advanced concepts."

### Starter Prompt 2: Foundation Building  
"Explain the 50/30/20 budgeting rule using examples from the documents. Include common pitfalls to avoid."

### Starter Prompt 3: Practical Application
"Generate a checklist for someone starting their first investment account, based on advice from at least three sources."

## Customization Guide
### For Different Audiences:
1. Students: Focus on debt management and starting savings.
2. Early Career: Emphasize retirement account setup and emergency funds.
3. Mid-Career: Highlight investment diversification and tax planning.

### Adding New Sources
1. Ensure documents are open-source or properly licensed
2. Update the source tracking system in prompts
3. Test for integration with existing materials

### Expanding Topics
#### Templates for New Topic Module:
"Analyze [NEW TOPIC] by:
1. Extracting key definitions from sources
2. Comparing approaches across documents
3. Creating practical application steps
4. Identifying knowledge gaps for further research"

### Assessment Tools
#### Self-Evaluation Quiz:
"1. What are the three main components of a balanced budget according to most sources?
2. How does compound interest differ from simple interest?
3. What factors influence your credit score?
4. Why is diversification important in investing?
5. At what age should retirement planning begin?"

### Progress Tracking
1. Pre-test and post-test knowledge checks
2. Practical application milestones
3. Source citation accuracy scoring

### Critical Thinking Framework
This project implements a _4-level critical thiking approach_:
1. Comprehension: Understading source material
2. Analysis: Comparing and contrasting information
3. Evaluation: Assessing source credibility and bias
4. Synthesis: Creating new insights and applications

### Example Framework Application:
"Topic: Emergency Funds
- Level 1: What do sources say about emergency funds?
- Level 2: How do recommendations differ by source?
- Level 3: Why might these differences exist?
- Level 4: How would you adapt this advice for different income levels?"

## Key Insights & Findings
### Discoveris from AI-Assisted Learning
1. Pattern Recognition: AI identified consistend advice across all government sources on basic principles.
2. Gap Analysis: Highlighted areas where sources provided conflicting or incomplete guidance.
3. Practical Synthesis: Generated actionable plans combining multiple sources recommendations.

## Prompt Engineering Lessons:
1. Specificity matters: Detailed prompts yield more useful responses.
2. Source citation is crucial: Always request references to original material
3. Iterative refinement: Best results come from prompt adjustment based on initial outputs.

# Future Enhancements
Planned improvements include:
Interactive web version of the study guide
Additional source documents (international perspectives)
Video tutorial series on using NotebookLM for learning
Mobile-friendly quick reference guides
Community-contributed prompt library

# Contributing
We welcome contributions! Please see our Contributing Guidelines for details.
Fork the repository
Create a feature branch
Add your improvements
Submit a pull request

# Acknowledgments
1. Google for creating NotebookLM
2. Government agencies for providing open educational resources
3. The financial education community for ongoing work in this field


