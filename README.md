Dispatch Montreal

# Dispatch Montreal

Dispatch Montreal is a digital emergency response platform designed to help protect vulnerable residents during climate-related emergencies such as power outages, heatwaves, and winter storms. The platform connects at-risk residents with trusted local volunteer hubs so community organizations can coordinate timely welfare checks when emergency services are under pressure.

## Problem

Montreal faces recurring climate and infrastructure-related risks that can leave vulnerable people without timely physical support. Existing alert systems may issue warnings, but they do not ensure that residents are actually safe or trigger direct follow-up. This creates a gap for seniors living alone, individuals with reduced mobility, and residents who depend on essential services during emergencies.

## Solution

Dispatch Montreal transforms local community centers and volunteer networks into coordinated emergency support hubs. The platform uses a secure resident registry, real-time emergency triggers, and a volunteer-facing dashboard to organize prioritized welfare checks. Volunteers can view assignments, update resident status, and escalate urgent cases when needed.

## Key Features

- Secure registry of vulnerable residents linked to nearby volunteer hubs
- Real-time trigger system based on emergency alerts and outages
- Prioritized volunteer dashboard for welfare check coordination
- Resident status updates and emergency escalation support
- Bilingual communication support
- Privacy-conscious and community-centered design

## Target Users

Dispatch Montreal is designed for vulnerable residents who may require proactive support during emergencies. It also supports volunteers, community organizations, and caregivers who need a structured and reliable way to coordinate safety check-ins.

## Project Goals

The project aims to deliver a functional MVP, validate the platform through a live simulation, and prepare for future deployment during high-risk seasonal emergencies. Its broader goal is to strengthen community resilience by combining digital coordination with trusted local action.

## Current Status

The project is currently in the planning and design phase. The problem, scope, stakeholders, user needs, and risk considerations have been identified, and the next step is to continue refining the system design and implementation plan.
# Dispatch Montreal Prototype

This repository contains the front-end prototype for our SOEN 6841 project.

## Interfaces
- coordinator-dashboard
- registration-page
- volunteer-page

## Branch Strategy
- main: stable version of the prototype
- feature/coordinator-dashboard: coordinator interface
- feature/registration-page: resident registration interface
- feature/volunteer-page: volunteer interface

## Configuration Management
We used GitHub for version control and configuration management.
Each team member worked on a separate feature branch.
Completed work was merged into the stable main branch.

## Run the app 
python3 -m http.server 5500
http://localhost:5500/
http://localhost:5500/coordinator-dashboard/
http://localhost:5500/registration-page/
http://localhost:5500/volunteer-page/