# SQL-Injection-Detection-Using-Deep-Learning

## Overview

This repository contains the implementation of a text classification model using the BERT Language Model to detect SQL Injection attacks on Apache Web Server. The project aims to improve security by detecting malicious SQL queries and enhancing log file analysis. The models were trained and tested using a publicly available dataset from [Kaggle](https://www.kaggle.com/datasets/sajid576/sql-injection-dataset), achieving high accuracy, precision, recall, and F1-score.

## Key Features

1. Deep Learning Models: Utilizes BERT Language Models for text classification.
2. High Accuracy: Achieves 99.84% with BERT in detecting SQL Injection.
3. Detection Method: Identifies SQL Injection attempts from web server logs.
4. Flexible Implementation: Compatible with Apache Web Server and tested with Damn Vulnerable Web Application (DVWA).
5. Public Dataset: Trained using a public dataset from Kaggle, containing a mix of normal and SQL Injection web requests.
