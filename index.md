---
layout: page
title: Home
nav_order: 1
description: A week-to-week description of the content covered in the course.
---

<link rel="stylesheet" href="css/index.css">

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

The schedule and dates listed below are tentative and may be subject to change. Check out the syllabus for course information.

</div>

<br>

| Week | Date | Lecture | Assignment |
| :--: | :--: | :--: | :--: |
| 1 | Tu 1/19 | 1. [Introduction & Data Science Lifecycle](https://drive.google.com/file/d/1YHhrSqMEV7LfRF5NVyaXcdcB58aJ01af/view?usp=sharing)| |
| | Th 1/21 | 2. [Logistics and Relational model & algebra](https://drive.google.com/file/d/1Czg4TDaerduUrDLbfOCnnv_8xyp_yeh6/view?usp=sharing) | |
| 2 | Tu 1/26 | 3. [Relational alg. contd. SQL intro](https://drive.google.com/file/d/1nojuIcgyd-npbLUp-65Mz0eW5PXPrgn_/view?usp=sharing) | |
|  | Th 1/28 | 4. [SQL intro, Views](https://drive.google.com/file/d/1IIewYULvLtaLxFAHwgdnwYLwZ29YAM11/view?usp=sharing) | |
| 3 | Tu 2/2 | 5.  [SQL subqueries and aggregation](https://drive.google.com/file/d/1qUHLUSmANCWrkdjAC45bNho1rXf1Kt_J/view?usp=sharing)| |
|  | Th 2/4 | 6. [More SQL: window functions, sampling, string manipulation](https://drive.google.com/file/d/1E1R8rmtNGVGXaLYwxk46EEvrMu6RHoMG/view?usp=sharing)| [Project 1](https://cs194.datahub.berkeley.edu/hub/user-redirect/git-sync?repo=https://github.com/cal-data-eng/sp21&subPath=proj/proj1/) (due 2/19) |
| 4 | Tu 2/9 | 7. [SQL updates, DDL, referential integrity, constraints](https://drive.google.com/file/d/1jSe4xsLHDEpquAa7tWC9Z3joWnmyPDtQ/view?usp=sharing) | |
|  | Th 2/11 | 8. [Index selection and performance tuning](https://drive.google.com/file/d/1yNaI5k5qzynklUl6ddGeCCSaNaHaJFHF/view?usp=sharing) | |
| 5| Tu 2/16 | 9. [Index selection and performance tuning (II)](https://drive.google.com/file/d/18WwVTzw7nQekUIcffr2d2x1iLFw1qAbc/view?usp=sharing) | Multivitamin 1 |
|  | Th 2/18 | 10. Data cleaning & integration | |
| 6 | Tu 2/23 | 11. Data cleaning & integration (II)| |
|  | Th 2/25 | 12. Context and Metadata | Project 2 |
| 7 | Tu 3/2 | 13. Alternative: Semistructured data (JSON/XML), Document and KV Stores | |
|  | Th 3/4 | 14. Alternative: Unstructured data & Search | |
| 8 | Tu 3/9 | 15. Alternative: Spreadsheets | Multivitamin 2 |
|  | Th 3/11 | 16. Alternative: Dataframes | |
| 9 | Tu 3/16 | 17. Alternative: Graph data: Property graph models, triples/RDF | Project 3 |
|  | Th 3/18 | 18. *Additional time for previous topics* | |
| | Tu 3/23 | **Spring Break** | |
| | Th 3/25 | **Spring Break** | |
| 10 | Tu 3/30 | 19. Triggers, streaming, sketching, and approximation | Multivitamin 3 |
|  | Th 4/1 | 20. Transactions and Recovery | Project 4 |
| 11 | Tu 4/6 | 21. Connectors, Logs, Pub-Sub/Queues, Orchestration, CDC & View Maintenance | |
|  | Th 4/8 | 22. *Additional time for previous topics* | |
| 12 | Tu 4/13 | 23. BI: OLAP, summarization, and visualization | Multivitamin 4 |
|  | Th 4/15 | 24. ML: Model training, serving, and monitoring | |
| 13 | Tu 4/20 | 25. Storage: File/object stores, Columnar vs. row, Compression, Exchange formats | Extra Credit Project |
|  | Th 4/22 | 26. Parallelization: Map-Reduce, Spark, Parallel DBMS, Dask/Modin | |
| 14 | Tu 4/27 | 27. Security and Privacy | |
|  | Th 4/29 | 28. *Additional time for previous topics* | Multivitamin 5 |
| 15 | Tu 5/4 | **RRR Week** | |
|  | Th 5/6 | **RRR Week** | |
