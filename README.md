# Named-Entity-Recognition-NER-Annotation

**Project Overview**

This project involves the annotation of named entities in a given text corpus for the purpose of training and evaluating Natural Language Processing (NLP) models. The task includes initial annotation, adjudication and refinement, and final evaluation stages to ensure high-quality annotated datasets. The annotations were categorized into six entity types: Person (PER), Facility (FAC), Geo-political entities (GPE), Location (LOC), Vehicle (VEH), and Organization (ORG).

**Technologies Used**

- **Programming Languages**: Python
- **Libraries**: NLTK, SpaCy, Flair, Stanza
- **Tools**: Jupyter Notebook, SLATE (annotation tool)

**Project Achievements**

- **High Annotation Accuracy:**
    - Achieved high consistency in annotations through a rigorous adjudication process, resulting in reliable and high-quality training data for NLP models.
- **Comprehensive Guidelines Development:**
    - Created detailed annotation guidelines that handled various edge cases and ensured consistency across multiple annotators.
- **Effective Model Evaluation**:
    - Successfully evaluated the performance of three widely-used NER models, providing insights into their strengths and weaknesses in handling multi-label named entity recognition tasks.

**Period**

- 2023.3 ~ 2023.6

**GitHub Repository**

- https://github.com/TommyYoungjunCho/Named-Entity-Recognition-NER-Annotation

# Project Details

---

1. **Initial Annotation**:
    - **Process**: Each group member independently annotated the text corpus using predefined guidelines. The annotations were then compiled into a single file.
    - **Categories**:
        - **Person (PER)**: Examples include "Barbican", "Captain", "scientists".
        - **Facility (FAC)**: Examples include "the Cambridge Observatory", "faculties".
        - **Geo-political entities (GPE)**: Examples include "Parsontown", "New York".
        - **Location (LOC)**: Examples include "the Moon", "the summit".
        - **Vehicle (VEH)**: Examples include "An express train", "the Projectile".
        - **Organization (ORG)**: Examples include "Representatives".
    - **Annotation Guidelines**:
        - **Named Entity Recognition**: The initial guide included examples and explanations for each category, specifying how to handle nested entities and special cases.
        - **Unusual Cases**: Detailed specific cases like personal pronouns, ambiguous terms, and nested annotations. For instance, "the lunar disc" was annotated as LOC with coordinates ((18,1), (18,3)).
        
2. **Adjudicated Annotation**:
    - **Process**: After receiving feedback and additional annotations from a machine learning model, the group reconciled differences in the annotations.
    - **Refinements**:
        - Included articles in the annotations for consistency.
        - Extended annotations to include modifying phrases or clauses.
        - Corrected inappropriate labels and aligned with the school's guidelines.
        - Maintained the exclusion of personal and objective pronouns from the PER category.
    - **Examples**:
        - "the seas" (including the article) was annotated as LOC.
        - "the former observers of the moon" (including the modifying clause) was annotated as PER.
        
3. **Improved Annotation**:
    - **Process**: Using the refined guidelines, the group annotated a new piece of text. This stage involved using the updated examples and rules to ensure consistency and accuracy.
    
4. **Evaluation Metrics**:
    - **Metric**: Implemented the F-Score to measure annotation consistency.
    - **Process**: Calculated the F-Score for each pair of annotations, including those provided by the machine learning model. This helped in evaluating the reliability and agreement between different annotators.
    
5. **Model Evaluation**:
- **Models Used**: Flair, SpaCy, Stanza
- **Process**: Ran these models on the adjudicated data and compared their outputs against the final annotations.
- **Scores**: Evaluated the models based on the F-Score to determine their accuracy in recognizing the annotated entities.

## Notion Portfolio Page
- [[Notion Portfolio Page Link](https://magic-taleggio-e52.notion.site/Portfolio-705d90d52e4e451488fb20e3d6653d3b)](#)
