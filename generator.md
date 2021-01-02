---
layout: default
permalink: generator
title: Generator - WorkflowHub
---

# Workflow Generator

The second axis of the WorkflowHub project targets the generation of 
**realistic** synthetic workflow traces with a variety of characteristics. 
The Workflow Generator, provided as part of the **[WorkflowHub Python 
package](http://workflowhub.readthedocs.io)**, uses recipes of workflows 
for creating different synthetic workflows based on distributions of 
workflow job runtime, and input and output file sizes. The resulting 
workflows are represented in the WorkflowHub JSON format, which is 
already supported by simulation frameworks such as 
[WRENCH](https://wrench-project.org).

The WorkflowHub Python package provides a number of workflow recipes for 
generating realistic synthetic workflow traces. Each recipe provides
different methods for generating synthetic, yet realistic, workflow 
traces depending on the properties that define the structure of the 
actual workflow.

The current list of [available workflow recipes](https://docs.workflowhub.org/en/latest/generating_workflows.html#workflow-recipes) 
include the following workflow applications:

- **1000Genome**: A high-throughput data-intensive bioinformatics 
                  workflow.
- **BLAST**: A high-throughput compute-intensive bioinformatics workflow.
- **BWA**: A high-throughput data-intensive bioinformatics workflow.
- **Cycles**: A high-throughput compute-intensive scientific workflow 
              for agroecosystems modeling.
- **Epigenomics**: A high-throughput data-intensive bioinformatics 
                   workflow.
- **Montage**: A high-throughput compute-intensive astronomy workflow.
- **Seismology**: A high-throughput data-intensive seismology workflow.
- **SoyKB**: A high-throughput data-intensive bioinformatics workflow.
- **SRASearch**: A high-throughput data-intensive bioinformatics workflow.

The Workflow Generator is constantly evolving and additional workflow
recipes will be added into new releases of the Python package.
