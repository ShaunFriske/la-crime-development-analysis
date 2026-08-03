# la-crime-development-analysis
Analyzing LAPD crime data to evaluate site selection safety for real estate development.

Overview
A data analytics pipeline designed to evaluate Los Angeles crime data (2020–present) to support real estate site selection focused strictly on low-crime development areas.

Workflow & Features
Automated Data Streaming: Programmatically pulls raw LAPD crime data directly from the City of LA Data Portal API.

Data Cleaning: Standardizes date formats, removes invalid victim ages, drops missing/zero-point coordinate records, and filters non-essential columns.

Risk Categorization: Classifies granular LAPD crime codes into Property Crime (burglary, theft, vandalism) and Violent Crime (assault, robbery, homicide).

Neighborhood Assessment: Ranks LAPD areas by safety metrics to identify optimal low-risk markets.

Trend Analysis: Tracks year-over-year incident trajectory (2020–2024) across neighborhoods.

Micro-Hotspot Mapping: Pinpoints high-density crime street segments to inform site-specific planning, security, and access design.
