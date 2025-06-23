# Harnessing the power of AIRR supercomputers for trusted research

Presented at [STEP-UP RSLondon 2025](https://step-up.ac.uk/events/step-up-2025/).

## Abstract

How can we use the country's most powerful supercomputers for research on sensitive data while keeping that data secure?

Complex AI models trained on large datasets are having a enormous impact in many research domains.
However, training and applying such models requires high performance hardware and specialist accelerators such as GPUs.
The new AI Research Resource (AIRR) has greatly expanded the availability of GPU-enabled compute to support large scale AI research in the UK.

Working with sensitive data requires high levels of security to ensure that the data is only accessible by approved researchers, and only for approved research.
Trusted Research Environments (TREs) provide secure analysis environments for working safely with sensitive data.
However, TREs do not provide the computational power and scaling that is required for the development and application of large models.
Conversely, high performance computing (HPC) platforms do not generally support TRE capabilities, and therefore cannot provide sufficient security for working with sensitive data.

In FRIDGE we are building a SATRE and NHS standards compliant, cross-platform TRE on AIRR; unlocking the power of these system for AI-driven research using sensitive data.

In our talk we will show our progress in enabling trusted research on AIRR and discuss,

- The unique challenges of creating a secure enclave on a shared resource
- How FRIDGE can be used to add new capabilities to existing TREs
- How we solve governance, when responsibility is shared between the HPC site and TRE operator
