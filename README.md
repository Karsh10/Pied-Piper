# Pied Piper  
*A real-time data engineering system built with Motia*

## What is Pied Piper?

**Pied Piper** is a real-time **data engineering platform** that listens to live public event
streams like:

- Wikipedia edits  
- Reddit activity  
- GitHub events  

It cleans and structures noisy data into **analytics-ready datasets**
using **Motia** 

## Why it Matters?

Public event streams are:
- Noisy    
- Unreliable  
- Full of duplicates and junk  

You **cannot directly trust raw events** for:
- Analytics  
- Dashboards  

## What Pied Piper does

Pied Piper fixes this by using Motia Step Abstraction that -

1. Ingests live events continuously  
2. Stores raw data safely (Bronze layer)  
3. Cleans it (Silver layer)  
4. Produces Industry Like Check (Gold layer)  
5. Exposes everything via APIs  

## Why Motia? 
EARLIER
- Kafka → streaming  
- Airflow → orchestration  
- Backend services → APIs
  
With **Motia**,everything is expressed using **Steps**.

- Ingestion = Step  
- Validation = Step  
- Routing = Step  
- APIs = Step  

## Architecture 
(Attached Picture)

## Tech Used
- Motia (event driven,orchestration,APIs)
- Python
- JSON (Bronze & Silver storage)
- Databricks
