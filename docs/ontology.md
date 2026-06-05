# The OpenEval Ontology
## The foundational elements of OpenEval
### Version 0.1
### Dated: 5th June, 2026


# Dataset

A collection of evaluation cases.

Examples:
- Customer Support Dataset
- Legal QA Dataset
- Coding Dataset
- Research Dataset


# Scenario

A real-world task.

Example:
- Customer requests refund
- A dataset contains many scenarios.


# Target

The thing being evaluated. We can also called it Evaluable.
Evaluable is anything capable of being evaluated, assessed, or measured. This implies that the target has enough clear data, parameters, or defining goals to make a logical judgment about its performance, validity, or value. 

Could be:
- LLM
- RAG System
- Agent
- Workflow
- Copilot
- Multi-Agent System

# Configuration

The settings of the system or target

Example:
model: GPT-5
temperature: 0

# Scenario

The Steps that were executed


# Run

One execution of a system.

Example:
- Refund Request #143


# Trace

Everything that happened during a run.

Includes:
- Inputs
- Outputs
- Tool Calls
- Retrievals
- Memory Access
- Latency
- Cost

# Span


# Evaluator

An Evaluator is a reliability assessment method. It takes evidence as input. It produces an assessment as output.

Example:
- Human Reviewer
- LLM Judge
- Custom Rules
- RAG Validator

Ontology:
Evaluator:
- id:
- name:
- version:
- description:
- type: (RULE_BASED, MODEL_BASED, HUMAN, HYBRID, CUSTOMER)
- purpose: 
- inputs: 
  - scenario: required
  - run: required
  - trace: optional
  - expected_output: optional
- reproducibility_metadata:
  - implementation:
  - provider:
  - model:
  - version


# Evaluation

An assessment performed on a run.
Evaluation includes a Metric and a Score.
Since we are dealing with probabilisitc systems, we would need Metric, Score, Scale, Confidence

Examples:
- Correctness
- Safety
- Groundedness
- Completeness

# Benchmark

A standardized set of evaluations.
Used for comparison.


# Reliability Profile

Aggregated reliability signal.
Not a single metric.
A composite.

Example Profile:
accuracy: 95
safety: 99
cost: 83
latency: 71
robustness: 88

# Regression

A degradation compared to a previous baseline.
