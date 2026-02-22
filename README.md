# NBA Injury GCP Setup
NBA Injury Data – GCP Ingestion Pipeline

This repository contains the code and configuration for building a cloud-based data ingestion pipeline for NBA injury data. The workflow uses Google Colab, Google Cloud Storage (GCS), and BigQuery to upload CSV injury files, store them in a structured bucket path, and load them into a raw BigQuery table for downstream analysis.

# The project includes:

- Automated CSV upload from Google Drive → GCS

- Dynamic folder partitioning by year/month/day

- BigQuery load jobs with autodetection and schema updates

- Scalable architecture suitable for analytics, EDA, and machine learning workflows

- Cloud-native setup designed for reproducibility and team collaboration

This setup supports a larger project focused on modeling, analyzing, and visualizing NBA injury trends from 2021–2026.
