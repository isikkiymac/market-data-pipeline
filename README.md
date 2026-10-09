# Market Data Analysis Pipeline

A data pipeline processing 1M+ rows of stock market data to identify trading patterns and compute technical indicators.

## Overview
Built a scalable pipeline that ingests raw stock market data, computes standard technical indicators, and stores results in a PostgreSQL database for efficient time-series querying and visualization.

## Tech Stack
- **Languages:** Python, SQL
- **Libraries:** Pandas, NumPy, Matplotlib
- **Database:** PostgreSQL
- **Data Volume:** 1M+ rows

## Key Features
- **Data ingestion** of 1M+ rows of historical stock data
- **Technical indicators implemented from scratch:**
  - SMA (Simple Moving Average)
  - RSI (Relative Strength Index)
  - Bollinger Bands
- **PostgreSQL schema design** optimized for time-series queries (indexed timestamp columns, partitioned tables)
- **Visualization dashboard** built with Matplotlib
- **Efficient querying** for date-range and symbol-based lookups

## Pipeline Architecture
Raw Data → Cleaning → Indicator Computation → PostgreSQL → Visualization


## What I Learned
- Handling large datasets with Pandas/NumPy efficiently
- Time-series database design and indexing strategies
- Financial indicator mathematics
- End-to-end data pipeline design

## Note
Source code is available upon request due to school policy restrictions. I'm happy to discuss the pipeline design, indicator implementations, and database schema in an interview.
