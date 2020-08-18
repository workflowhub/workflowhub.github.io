---
layout: default
permalink: json-format
title: JSON Format - WorkflowHub
---

# The WorkflowHub JSON Format

The WorkflowHub project uses a **common format** for representing workflow 
execution traces and generated synthetic workflows traces, so that workflow 
simulators and simulation frameworks (that provide support for WorkflowHub 
format) can use such traces interchangeably. 

This common format uses a JSON specification available in the **[WorkflowHub 
JSON schema GitHub](https://github.com/workflowhub/workflow-schema)** repository. 
The schema GitHub repository provides detailed explanation of the WorkflowHub 
JSON format (including required fields), and a validator script for verifying 
the compatibility of traces.

Below, is a visualization of the schema version `1.0`:

<iframe src="https://workflowhub.org/json-schema-viewer/basic.html#" 
  style="width: 100%; border: 0; min-height: 40em"></iframe>
