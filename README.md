# SystemsAnalisis
Repository to store all documents and things relationated with System Analysis course.

## Members:
- Edward Julian Garcia Gaitan
- Jaider Camilo Carvajal Marin
- Nelson David Posso Suárez
# Systems Analysis — Drawing with LLMs (Kaggle)

This repository documents the systems analysis and design work developed as part of the *Systems Analysis & Design (2025-I)* course at Universidad Distrital Francisco José de Caldas. The project takes the Kaggle competition [**Drawing with LLMs**](https://www.kaggle.com/competitions/drawing-with-llms) as its case study. This competition challenges participants to build generative AI models capable of producing SVG illustrations based on text prompts—merging natural language understanding with image generation.

## Repository Purpose

The main goal of this project is to apply systems thinking principles to understand, structure, and propose a robust solution to the competition’s problem, through a comprehensive process of analysis and design.

---

## Repository Structure

### Workshop 1 — *System Analysis*

This phase focuses on understanding the problem as a system. It involves:
- Defining system boundaries and identifying its core function.
- Mapping key components, their inputs, processes, and outputs.
- Exploring interactions, randomness, sensitivity to change, and emergent complexity.
- Laying the foundation for informed design decisions through systems thinking.

### Workshop 2 — *System Design*

Based on the findings from Workshop 1, this phase outlines a system design that includes:
- **System Requirements**: Translating insights into measurable functional and non-functional requirements (e.g., prompt interpretation, SVG generation, performance, scalability).
- **High-Level Architecture**:
  - Core modules: data ingestion, preprocessing, LLM-based generation, SVG synthesis, output validation.
  - Component responsibilities and data flow.
  - Emphasis on modularity, maintainability, and scalability.
- **Chaos and Sensitivity Mitigation**:
  - Techniques like robust prompt engineering, controlled generation, postprocessing, and system monitoring.
- **Technology Stack and Implementation Sketch**:
  - Recommended tools: Python, Hugging Face Transformers, SVG libraries.
  - Preliminary implementation plan and design pattern references.

### Workshop 3 — Simulation and Evaluation

This phase tests the proposed system design under simulated conditions:

- **Simulation Focus:** Evaluating how the system behaves with varied and complex prompts, edge cases, and performance load.
- **Key Scenarios:** Functionality, robustness, quality assurance, scalability, and performance.
- **System Behavior:** The modular design allowed for stable behavior even when unexpected or malformed inputs were introduced.
- **LLM Sensitivity:** Confirmed the system's chaotic behavior with minimal changes to prompts, as predicted in previous workshops.
- **Results:** Most SVGs were valid and generated quickly. Some visual inconsistencies highlight areas for future improvement.

### Catch-up

A consolidation document that integrates the work from Workshop 1 and Workshop 2. It provides a holistic view of both the system analysis and design, reinforcing the systemic approach and design rationale.

---

## Suggested Technologies

- Python
- Hugging Face Transformers
- SVG manipulation libraries
- Kaggle Notebooks / Google Colab

---

## Methodological Approach

- Systems thinking
- Sensitivity and chaos analysis
- Modular and scalable system design
- Prompt engineering and generative output evaluation

---

## License

This project is licensed under the MIT License. See the [LICENSE](../LICENSE) file for more details.
