---
layout: page
title: Home
tagline: Apache Project !
---
<!--
{% comment %}
Licensed to the Apache Software Foundation (ASF) under one or more
contributor license agreements.  See the NOTICE file distributed with
this work for additional information regarding copyright ownership.
The ASF licenses this file to you under the Apache License, Version 2.0
(the "License"); you may not use this file except in compliance with
the License.  You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
{% endcomment %}
-->

{% include JB/setup %}

## Apache SystemML

SystemML provides declarative large-scale machine learning (ML) that aims at flexible specification 
of ML algorithms and automatic generation of hybrid runtime plans ranging from single node, 
in-memory computations, to distributed computations on Apache Hadoop and  Apache Spark. 
ML algorithms are expressed in a R or Python syntax, that includes linear algebra primitives, statistical functions, 
and ML-specific constructs. This high-level language significantly increases the productivity of data scientists 
as it provides (1) full flexibility in expressing custom analytics, and (2) data independence from the underlying 
input formats and physical data representations. Automatic optimization according to data characteristics such as 
distribution on the disk file system, and sparsity as well as processing characteristics in the distributed environment 
like number of nodes, CPU, memory per node, ensures both efficiency and scalability. 
