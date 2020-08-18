---
layout: default
permalink: simulator
title: Simulator - WorkflowHub
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

In this page, we keep a list of _open source_ workflow management systems 
simulators and simulation frameworks that provide support for 
**[The WorkflowHub JSON format](/json-format)**,
which is used for generating [workflow execution traces](/traces), and 
synthetic workflows obtained with the [workflow generator](/generator).

#### Open Source Simulator Repositories

We are constantly seeking for additional simulators to be added to the list 
below. If you want to also have your simulator listed in this page, please 
contact us at <simulators@workflowhub.org>. Note that each simulator should 
be compatible with [The WorkflowHub JSON format](/json-format).

| Simulator / Framework | Description |  |
|---|---|---|
{%- for s in site.data.simulators %}
| [{{ s.name }}]({{ s.website }}) | {{ s.description}} | <img src="https://travis-ci.org/{{ s.travis }}"/> <img src="{{ s.release }}"/> |
{%- endfor -%}
