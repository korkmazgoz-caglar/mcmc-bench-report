# MCMC Benchmark Report
<a href="https://raw.githubusercontent.com/korkmazgoz-caglar/mcmc-bench-report/pdf-tectonic/mcmc-bench-report.pdf">
<img src="https://img.shields.io/badge/View-PDF_(Tectonic)-red?style=flat-square&logo=adobeacrobatreader&logoColor=white" alt="View the report PDF (Tectonic)"/>
</a>
<a href="https://raw.githubusercontent.com/korkmazgoz-caglar/mcmc-bench-report/pdf-tinytex/mcmc-bench-report.pdf">
<img src="https://img.shields.io/badge/View-PDF_(TinyTeX)-red?style=flat-square&logo=adobeacrobatreader&logoColor=white" alt="View the report PDF (TinyTeX)"/>
</a>
<a href="https://github.com/korkmazgoz-caglar/mcmc-bench-report/actions/workflows/compat.yml">
<img src="https://img.shields.io/github/actions/workflow/status/korkmazgoz-caglar/mcmc-bench-report/compat.yml?label=Compatibility%3A%20Linux%20%7C%20macOS%20%7C%20Windows&style=flat-square" alt="Compatibility: Linux | macOS | Windows"/>
</a>
This repository contains the LaTeX source, figures, and preserved benchmark outputs for the report *Benchmarking of Sampling Methods for Probabilistic Calibration in Gravity-Driven Mass Flow Modeling*. The benchmark implementation and workflow are available in the [mcmc-bench repository](https://github.com/thealanjason/mcmc-bench). The report uses a LaTeX template based on [latex-mimosis](https://github.com/Pseudomanifold/latex-mimosis).

## Contents

1. Introduction
   - Motivation
   - Research Questions
   - Outline
2. Background and Related Work
   - The Inverse Problem
   - The Bayesian Approach to the Inverse Problem
   - The Bayesian Calibration Pipeline
   - Sampling Methods for Bayesian Inference
3. Benchmarking Sampling Methods
   - Implementation Details
   - Sampler Integration
     - Random-Walk Metropolis-Hastings
     - emcee
     - dynesty
     - PyMC Slice and Sequential Monte Carlo
4. Evaluation
   - Experimental Setup
   - Metrics
     - Posterior Agreement
     - Convergence
     - Efficiency
   - Results
     - Posterior Agreement
     - Convergence Diagnostics
     - Computational Efficiency
   - Discussion
     - Limitations
5. Summary and Future Work
   - Summary
   - Future Work
