---
nav_order: 3
title: Data export
layout: default
parent: Reports
---

# Exporting your data
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## Export data

{% capture export %}
7. Click on `Data Exports, Reports, and Stats` on the left-hand navigation.
8. Click `Export Data`. Most major statistical package formats are represented: CSV, SPSS, STATA and R.
9. Note also the de-identification options, especially the option to Remove all tagged identifier fields.
10. Click `Cancel` (don’t export the data).
{% endcapture %}
{% include card.html header="Export de-identified data" text=export %}

{% include figure.html img="export-data.png" alt="The REDCap data export options" caption="The REDCap data export options" width="100" %}

{% include alert.html text="If you need to see what changes have been made to the structure or data of your project, use the Logging tool on the Applications List" color="primary" %}
