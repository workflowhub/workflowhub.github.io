---
layout: default
---

# Workflow Simulator

An alternative to conducting scientific workflow research via real-world 
experiments is to use simulation, i.e., implement a software artifact that 
models the functional and performance behaviors of software and hardware 
stacks of interest. 

Simulation is used in many computer science domains and can address the 
limitations of real-world experiments, e.g. they are confined to application 
and platform configurations available at hand, and thus cover only a small 
subset of the relevant scenarios that may be encountered in practice.

The third axis of the WorkflowHub project fosters the use of simulation for
the development, evaluation, and verification of scheduling and resource 
provisioning algorithms (e.g., multi-objective function optimization, etc.), 
evaluation of current and emerging computing platforms (e.g., clouds, IoT,
extreme scale, etc.), among others.
 

## List of Workflow Simulators

In this page, we keep a list of workflow management systems simulators that 
provide support for **[The WorkflowHub JSON format](json.html)**, which is 
used for generating [workflow execution traces](traces.html), and synthetic 
workflows obtained with the [workflow generator](generator.html).

| Simulator | Description | Website |
| --- | --- | --- |
| WRENCH | A simulation framework distributed as a C++ library           | [https://wrench-project.org](https://wrench-project.org)
| WRENCH-Pegasus | A WRENCH-based simulator of the Pegasus WMS           | [https://github.com/wrench-project/pegasus](https://github.com/wrench-project/pegasus)
| WRENCH-WorkQueue | A WRENCH-based simulator of the WorkQueue framework | [https://github.com/wrench-project/workqueue](https://github.com/wrench-project/workqueue)
