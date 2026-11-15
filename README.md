# Defeasible Ontologies
Three Domain-Scale Ontologies for Modelling Exceptions and Evaluating Non-Monotonic Reasoning

# Overview

This repository provides a collection of three domain-scale defeasible ontologies developed as research artefacts for investigating the representation of default knowledge, exceptions, and non-monotonic reasoning in ontologies.

Traditional ontologies, particularly those based on classical Description Logics, rely on monotonic reasoning. Once a conclusion has been derived from a knowledge base, adding new knowledge cannot invalidate that conclusion. While this property provides a sound foundation for knowledge representation, it presents limitations when modelling domains containing typical behaviours, contextual exceptions, and knowledge that admits exceptions to previously established rules.

Defeasible reasoning addresses this limitation by allowing conclusions to be withdrawn when more specific or exceptional information becomes available.

The ontologies in this repository explore how defeasible knowledge can be systematically incorporated into realistic domain models and how these models can be used to evaluate non-monotonic reasoning approaches.

The collection consists of three ontologies:
 - Access Control and Policy (ACP) Ontology
 - Movie Ontology
 - Education and Learning Pathways Ontology

Together, these ontologies provide diverse knowledge representation scenarios for investigating defeasible reasoning across different application domains.
The repository is intended to serve as a reusable research resource for researchers, ontology engineers, and developers working on defeasible Description Logics, non-monotonic reasoning, and Semantic Web technologies.

# Research Motivation

Ontologies provide a formal and structured means of representing domain knowledge. However, real-world knowledge is rarely composed entirely of universally applicable facts and rules. Many domains rely on general assumptions that hold under normal circumstances but admit exceptions.

For example:

1. Access Control: Employees are typically permitted to access certain organisational resources, but access may be restricted under specific circumstances or overridden by more specific security policies.
2. Movies: Movies typically belong to particular genres or exhibit common characteristics, although individual movies may deviate from these expectations.
3. Education: Students typically follow established learning pathways, but alternative routes, exemptions, prerequisites, and individual circumstances can introduce exceptions to standard progression rules.

Representing such knowledge using only classical ontological axioms can result in overly restrictive models or require extensive enumeration of exceptional cases.

Defeasible ontologies offer an alternative by distinguishing between strict knowledge, which must always hold, and defeasible knowledge, which represents general expectations that may be overridden.Despite the growing interest in non-monotonic reasoning, there remains a need for realistic and sufficiently expressive ontology resources that can support the systematic development, testing, and evaluation of defeasible reasoning approaches.

This repository addresses that need by providing three domain-scale ontologies developed to investigate the practical application of defeasible knowledge representation.

# Reasoning Infrastructure
The ontologies are developed and investigated using the following tools and technologies:
| Tool / Technology | Purpose |
|---|---|
| [Protégé](https://protege.stanford.edu/) | Ontology development, editing, and management. |
| [OWL 2](https://www.w3.org/TR/owl2-overview/) | Formal language for representing and structuring ontological knowledge. |
| Description Logics (DLs) | Logical foundation for ontology representation and formal reasoning. |
| Defeasible Inference Platform [DIP](https://github.com/kodymoodley/defeasibleinferenceplatform) | Supports defeasible reasoning and inference over ontology knowledge bases. |
| Rational Closure | Non-monotonic reasoning approach for handling default knowledge, exceptionality, and exceptions. |
| [OOPS!](https://oops.linkeddata.es/) | Structural ontology verification and detection of potential modelling pitfalls. |
| Competency Questions (CQs) | Validation mechanism for evaluating ontology coverage, expressivity, and reasoning outcomes. |
