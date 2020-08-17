---
layout: default
permalink: traces
---

# Workflow Execution Traces

Workload traces are widely used to profile and characterize workflow executions, 
and to build distributions of workflow execution behaviors, which are used to 
evaluate methods and techniques in simulation or in real conditions.

The first axis of the WorkflowHub project targets the collection and curation of
**open access** production workflow executions from various scientific applications 
shared in a common trace format.

## List of Workflow Execution Traces

In this page, we keep a list of _open access_ workflow execution trace repositories 
that host traces compliant with the **[The WorkflowHub JSON format](json.html)** for 
describing workflow executions. We are constantly seeking for additional workflow 
execution traces for refining or developing new workflow recipes for the WorkflowHub's 
[workflow generator](/generator).

Workflow execution traces are organized into sub-folders within the repositories. 
Each sub-folder represents a workflow application, which itself contains sub-folders 
for workflow executions in different computing platforms. For each workflow 
application, a `README.md` file provides detailed description of the workflow
structure and pointers to relevant material.

#### Open Access Trace Repositories

| Repository | # Applications | # Computing Platforms | # Traces | | 
| --- | --- | --- | --- | --- |
{%- for t in site.data.traces %}
| [{{ t.name }}]({{ t.website }}) | {{ t.applications}} | {{ t.platforms }} | {{ t.traces }} | <img src="https://travis-ci.org/{{ t.travis }}"/> |
{%- endfor -%}

