---
layout: page
title: Home
nav_order: 1
description: A week-to-week description of the content covered in the course.
---

# Data Engineering
{: .mb-2 }
UC Berkeley, Spring 2021
{: .mb-0 .fs-6 .text-grey-dk-000 }

<div>

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
<div class="role">
  {% for staffer in instructors %}
  {{ staffer }}
  {% endfor %}

</div>

This website is under construction. Check out <a href="https://docs.google.com/document/d/1hXcZY9OKvAbHDMBZnjYBZ08KM8Sry6TsMEno0mJt5tI/edit"> this document </a> for class information. The schedule and dates listed below are tentative and may be subject to change.

<br>

| Week | Date | Lecture | Assignment |
| :--: | :--: | :--: | :--: |
| 1 | Tu 1/19 | 1. Introduction | |
| | Th 1/21 | 2. Relational model & algebra; SQL Intro | |
| 2 | Tu 1/26 | 3. SQL subqueries and aggregation | |
|  | Th 1/28 | 4. SQL DDL, Database design, Views | |
| 3 | Tu 2/2 | 5. Data Integrity: FDs, Constraints & Triggers | |
|  | Th 2/4 | 6. Index selection, Query processing & optimization | |
| 4 | Tu 2/9 | 7. Index selection, Query processing & optimization (II) | |
|  | Th 2/11 | 8. Data cleaning & integration | |
| 5| Tu 2/16 | 9. Data cleaning & integration (II) | |
|  | Th 2/18 | 10. Context and Metadata | |
| 6 | Tu 2/23 | 11. *Additional time for previous topics* | |
|  | Th 2/25 | 12. Alternative: Semistructured data (JSON/XML), Document and KV Stores | |
| 7 | Tu 3/2 | 13. Alternative: Semistructured data (JSON/XML), Document and KV Stores (II) | |
|  | Th 3/4 | 14. Alternative: Unstructured data & Search | |
| 8 | Tu 3/9 | 15. Alternative: Spreadsheets | |
|  | Th 3/11 | 16. Alternative: Dataframes | |
| 9 | Tu 3/16 | 17. Alternative: Graph data: Property graph models, triples/RDF | |
|  | Th 3/18 | 18. *Additional time for previous topics* | |
| | Tu 3/23 | **Spring Break** | |
| | Th 3/25 | **Spring Break** | |
| 10 | Tu 3/30 | 19. Streaming, sketching, and approximation | |
|  | Th 4/1 | 20. SQL Modifications, Transactions and Recovery | |
| 11 | Tu 4/6 | 21. Connectors, Logs, Pub-Sub/Queues, Orchestration, CDC & View Maintenance | |
|  | Th 4/8 | 22. *Additional time for previous topics* | |
| 12 | Tu 4/13 | 23. BI: OLAP, summarization, and visualization | |
|  | Th 4/15 | 24. ML: Model training, serving, and monitoring | |
| 13 | Tu 4/20 | 25. Storage: File/object stores, Columnar vs. row, Compression, Exchange formats | |
|  | Th 4/22 | 26. Parallelization: Map-Reduce, Spark, Parallel DBMS, Dask/Modin | |
| 14 | Tu 4/27 | 27. Security and Privacy | |
|  | Th 4/29 | 28. *Additional time for previous topics* | |
| 15 | Tu 5/4 | **RRR Week** | |
|  | Th 5/6 | **RRR Week** | |
