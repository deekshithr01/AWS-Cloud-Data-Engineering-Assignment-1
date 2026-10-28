# AWS Cloud & Data Engineering – Assignment 1

## Overview
This repository contains my Practical Assignment 1 report completed as part of the AWS Cloud & Data Engineering training program at Jain (Deemed-to-be) University.

The assignment covers SQL practice, Linux commands, Amazon S3 storage, AWS IAM, AWS Glue Data Catalog, Amazon Athena, and AWS Glue Studio Visual ETL.

## Objectives
- Practise SQL queries, filtering, sorting, grouping, and aggregation.
- Perform Linux command-line operations.
- Upload and organize employee CSV data in Amazon S3.
- Understand IAM roles and permissions.
- Create databases and tables using AWS Glue Data Catalog.
- Query employee data using Amazon Athena.
- Design a visual ETL workflow using AWS Glue Studio.

## Technologies Used
- Amazon Web Services (AWS)
- Amazon S3
- AWS IAM
- AWS Glue Data Catalog
- AWS Glue Studio
- Amazon Athena
- SQL
- Linux

## Implementation Summary
The practical work includes SQL and Linux exercises, employee dataset preparation, Amazon S3 storage setup, Glue Data Catalog table creation, and Athena queries.

The Glue Studio workflow was designed with a Data Catalog source, a Drop Fields transformation, and an Amazon S3 target configured for Parquet format with Snappy compression.

## Results and Limitations
The available evidence confirms successful S3 data uploads, Glue Data Catalog database and table creation, and Athena query results.

Attempts to create or update the AWS Glue crawler and ETL job were blocked by an `AccessDeniedException`. Successful end-to-end ETL execution was therefore not verified.

## Repository Contents
- `README.md` – Assignment overview and documentation.
- `HCL_Cloud_Data_Engineering_Assignment.pdf` – Detailed practical report with screenshot evidence.

## AWS Region
Asia Pacific (Mumbai) — `ap-south-1`

## Student Details
- **Name:** Deekshith R
- **USN:** 23BTREC005
- **Department:** Electronics and Communication Engineering (ECE)
- **Institution:** Jain (Deemed-to-be) University
- **Batch:** 2023–2027

## Purpose
This repository is intended for academic submission and documentation of practical learning in cloud and data engineering.
