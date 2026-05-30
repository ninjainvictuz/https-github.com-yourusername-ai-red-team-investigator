# https-github.com-yourusername-ai-red-team-investigator
AI Red Team Investigator uses Bright Data web intelligence to discover external cyber threats, map attack surface exposure, generate explainable risk scores, and provide actionable security recommendations for enterprise security teams.
# AI Red Team Investigator

## Overview

AI Red Team Investigator is an AI-powered External Exposure Intelligence Platform built for the Bright Data Hackathon Security & Compliance Track.

The platform continuously investigates publicly available cyber threat signals, attack surface indicators, phishing campaigns, brand impersonation risks, and exposure-related intelligence across the open web.

Using Bright Data's web intelligence infrastructure, the system transforms unstructured web data into explainable cyber risk assessments and actionable recommendations for enterprise security teams.

---

## Problem Statement

Security teams rely heavily on internal telemetry such as SIEMs, EDRs, and vulnerability scanners.

However, many critical risks emerge externally:

* Phishing campaigns
* Brand impersonation attacks
* Public breach discussions
* Credential exposure
* Infrastructure disclosures
* Open-source intelligence signals

These signals often appear on the public web long before they are detected internally.

---

## Solution

AI Red Team Investigator combines:

* Bright Data SERP API
* Bright Data Web Unlocker
* OpenRouter LLMs
* Automated Threat Classification

to create structured threat intelligence reports.

Users enter a domain such as:

* tesla.com
* okta.com
* lastpass.com

The platform automatically:

1. Collects public threat intelligence
2. Identifies attack surface indicators
3. Classifies threat categories
4. Calculates explainable risk scores
5. Generates AI-driven recommendations

---

## Key Features

### Attack Surface Mapping

Analyze publicly available attack surface indicators.

### Threat Intelligence Collection

Collect live security-related web intelligence.

### Explainable Risk Scoring

Weighted risk calculations with transparent breakdowns.

### Evidence-Based Findings

Source-backed intelligence cards with confidence ratings.

### Analyst Verdicts

AI-generated security assessments.

### Recommendation Engine

Actionable remediation guidance.

### Continuous Monitoring

Track domains for ongoing exposure analysis.

---

## Bright Data Integration

This project uses:

### Bright Data SERP API

* Collects public search intelligence
* Discovers threat-related signals

### Bright Data Web Unlocker

* Retrieves public web content from protected sources
* Improves source coverage

---

## Technology Stack

Frontend

* React
* TypeScript
* Vite
* Tailwind CSS

Backend

* Node.js
* Express.js

AI

* OpenRouter
* GPT-4o Mini

Data Collection

* Bright Data SERP API
* Bright Data Web Unlocker

---

## Architecture

User Domain Input
↓
Bright Data Intelligence Collection
↓
Threat Signal Processing
↓
AI Risk Analysis
↓
Threat Classification
↓
Risk Scoring
↓
Recommendations
↓
Executive Report

---

## Demo Domains

* tesla.com
* okta.com
* lastpass.com
* ticketmaster.com

---

## Installation

### Frontend

npm install

npm run dev

### Backend

npm install

node server.js

---

## Environment Variables

OPENROUTER_API_KEY=your_key

VITE_BRIGHTDATA_API_KEY=your_key

---

## License

MIT License
