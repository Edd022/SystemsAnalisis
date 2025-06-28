# Systems Analysis & Design — Workshop No. 3: Simulation and Evaluation

This document presents the simulation and evaluation phase for the "Drawing with LLMs" Kaggle competition. It was developed as part of the Systems Analysis & Design course (Semester 2025-I) at Universidad Distrital Francisco José de Caldas. This workshop builds upon the foundations of Workshop No. 1 (System Analysis) and Workshop No. 2 (System Design), aiming to test the system’s real-world performance through controlled experimentation.

---

## Competition Context

The simulation focuses on the Kaggle competition: Drawing with LLMs. This competition challenges participants to develop generative AI models capable of producing SVG drawings from text prompts. The task requires integrating natural language understanding and visual representation, pushing the limits of prompt interpretation, system reliability, and output consistency.

---

## Simulation Process

The simulation was designed to evaluate the system's behavior under varied and unpredictable conditions, testing both functionality and resilience. It aimed to determine whether the system could:

- Successfully process prompts of different lengths, formats, and complexity.
- Maintain performance and generate valid outputs even under stress.
- Handle malformed or edge-case prompts without crashing.
- Produce SVGs that adhere to competition rules regarding file size, XML validity, and rendering capability.

To guide this process, five simulation scenarios were created, each aligned with a specific module in the system design:

- **M1 – Data Ingestion:** Receiving and managing prompts with varying formats and structures.
- **M2 – Text Processing:** Managing noise, ambiguity, or inconsistencies in language.
- **M3 – LLM Generation:** Generating SVGs based on prompts, while observing how slight changes in input affect output.
- **M4 – Validation:** Ensuring that all generated outputs comply with technical constraints (size, format, syntax).

Basic constraints were established: SVG files must be under 10,000 bytes, outputs must be valid XML, and generation should remain under 1 second per prompt. The system’s ability to remain operational in all scenarios was a key success factor.

---

## Observations and Findings

The simulation yielded the following key insights:

- The system remained stable and responsive throughout the tests.
- Most SVG outputs were valid, even when dealing with prompts that varied significantly in complexity.
- The modular architecture (defined in Workshop 2) allowed isolated testing and debugging of individual components, confirming its effectiveness.
- As expected from the sensitivity analysis in Workshop 1, small variations in input often resulted in drastically different outputs—highlighting chaotic behavior typical in generative systems.
- Performance metrics were positive overall, with fast generation times and proper scaling under simulated concurrent use.
- Some visual inconsistencies were noted in complex prompts, pointing to potential improvements in fine-tuning the language model or refining prompt processing.

---

## Systems Analysis Concepts Applied

This workshop continued the application of systems thinking principles:

- **Modularity:** Enabled error isolation and targeted testing of individual components.
- **Sensitivity and Chaos Theory:** Demonstrated how small changes in input conditions led to divergent results, reinforcing the need for robust handling of uncertainty.
- **Feedback and Adaptation:** Highlighted the value of potential feedback mechanisms for output validation and refinement.
- **Robustness and Scalability:** Tested the system’s behavior under stress, confirming its design could handle complexity and load without degradation.

---

## Final Simulation Report

The full simulation report, which includes scenario definitions, system behavior observations, and recommendations for future improvements, can be accessed below:
[Workshop_3_Kaggle Competition.pdf](https://github.com/Edd022/SystemsAnalisis/blob/main/Workshop_3/Workshop_3%20Workshop_3_Kaggle%20Competition.pdf)
