# ÍRIS Taxonomy

**An Interactive Decision-Support Prototype for LLM Output Evaluation**

ÍRIS is a multidimensional taxonomy designed to support researchers and developers in selecting evaluation strategies for Large Language Model (LLM) outputs according to the characteristics of their evaluation scenarios.

This repository hosts an interactive prototype that allows users to explore relationships between evaluation contexts and methods identified in the scientific literature.

## Research Background

The ÍRIS taxonomy was developed from an evidence base comprising **47 primary studies published between 2023 and April 2026**, resulting in **179 standardized evidence records**.

Associations between taxonomy dimensions were investigated using *Support*, *Confidence*, and *Lift*, enabling the identification of recurring and emerging relationships.

## How It Works

The interactive application follows four main dimensions:

**Application Domain → Model Task → Quality Aspect → Evaluation Method Family**

A complementary relationship connects **Quality Aspect → Automation Level**.

Users can explore the taxonomy by selecting categories from the form or clicking directly on the interactive diagram. The application highlights relevant connections and presents the statistical evidence associated with them.

Associations are classified as:

- **Recurring:** Support ≥ 4 and Lift > 1.
- **Emerging:** Support between 2 and 3 and Lift > 1.

These associations represent pairwise relationships observed in the literature, not statistically validated joint relationships across an entire path.

## Purpose and Limitations

ÍRIS is intended as a decision-support mechanism, not an automatic system for determining the universally best evaluation method.

The prototype helps researchers explore empirical evidence and identify potentially relevant evaluation strategies. Final methodological decisions remain the responsibility of the researcher.

## Research Context

Developed as part of a Master's research project in Computer Science at the **Federal University of Ceará (UFC), Brazil**, within the MDCC graduate program.

**Researcher:** Gabriel Rudan Sales Matos

## Data Availability

The evidence base is preserved on Zenodo. The dataset DOI and corresponding bibliographic reference can be added here.

## Status

This repository contains a research prototype developed to demonstrate the practical application of the ÍRIS taxonomy. Further evaluation, refinement, and extensions are planned.
