AI-Based Early Warning and Landslide Risk Monitoring System
Ministry of Development of North Eastern Region (MDoNER)

This project is an AI-based software system for monitoring landslide-prone areas in the North Eastern Region of India.

Features
Monitor landslide-prone locations
Store rainfall and soil data
Store sensor information
Record previous landslide events
Predict landslide risk using AI/ML
Generate early-warning alerts
Database

The project uses PostgreSQL.

Main database tables:

monitoring_locations
sensors
environmental_readings
landslide_events
risk_predictions
alerts
system_users
Setup

Create the database:

CREATE DATABASE landslide_monitoring;


Then run the SQL file:

psql -U postgres -d landslide_monitoring -f schema.sql

Risk Levels
LOW – Normal monitoring
MEDIUM – Increase monitoring
HIGH – Issue warning
CRITICAL – Immediate action
Project Status

Prototype / Sample Project

The sample database contains dummy data for testing and demonstration purposes.
