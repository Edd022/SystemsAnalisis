# Systems Analysis & Design - Workshop No. 2: System Design

This document outlines the system design process undertaken for the "Drawing with LLMs" Kaggle competition, as part of the Systems Analysis & Design course (Semester 2025-I) at Universidad Distrital Francisco José de Caldas. This workshop builds upon the systemic analysis performed in [Workshop No. 1: System Analysis](https://github.com/Edd022/SystemsAnalisis/blob/main/Workshop_1/Workshop_No__1_Kagle_Systems_Analysis_of_Drawing_with_LLMs.pdf).

## Competition Context

The design is targeted towards the Kaggle competition: [Drawing with LLMs](https://www.kaggle.com/competitions/drawing-with-llms/overview). This competition challenges participants to develop generative AI models capable of creating SVG drawings that visually represent a wide range of concepts, exploring the intersection of natural language understanding and image generation.

## System Design Process

The design process for Workshop 2 commenced by thoroughly **reviewing the findings from Workshop No. 1**. This included a summary of critical constraints, data characteristics, identified system elements, their relationships, sensitivity considerations, and any chaos theory implications previously analyzed.

Based on this analytical foundation, the following steps were undertaken to develop the system design:

1.  **Defining System Requirements:** The insights from Workshop 1 were translated into measurable design requirements, encompassing both functional aspects (e.g., SVG generation, prompt interpretation) and non-functional aspects (e.g., performance targets, reliability standards, scalability, and maintainability).

2.  **Developing High-Level Architecture:** A system architecture was proposed to structure the solution. This involved:
    * Creating an architectural diagram outlining core components (e.g., data ingestion, text preprocessing, LLM-based generation, SVG synthesis and validation, output management) and the flow of data between them.
    * Defining the responsibilities of each module.
    * Ensuring the design integrated systems engineering principles such as modularity, scalability, and maintainability.

3.  **Addressing Sensitivity and Chaos:** Strategies were incorporated into the design to mitigate unpredictable behaviors (chaos) and manage highly sensitive elements identified in Workshop 1. This included considerations for robust prompt engineering, controlled LLM generation, defensive postprocessing, and comprehensive monitoring/logging.

4.  **Proposing a Technical Stack and Implementation Sketch:**
    * Recommended tools, frameworks, and programming languages (e.g., Python, Hugging Face Transformers, SVG-specific libraries) were selected with justification.
    * A brief plan was outlinedSketching out how components would be implemented and integrated, referencing any chosen design patterns.

This structured design process aimed to build a robust and well-engineered system capable of addressing the competition's challenges, directly informed by the preceding systems analysis.

## Final System Design Document

The complete System Design Document (SDD) in PDF format, detailing the architecture, design decisions, component descriptions, and implementation plan for the "Drawing with LLMs" competition, is available at the following link. This document is located in the `Workshop_2_Design` folder of this repository, as per the workshop requirements.

**[📄 View the Final System Design Document (PDF)](https://drive.google.com/file/d/1OlzdcwXTsKgT_c9LMbqdfZIPjz9JBiTy/view?usp=sharing)**.

