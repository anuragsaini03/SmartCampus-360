Smart Campus 360

AI + IoT Smart Campus Intelligence

Team: APEX DEVS
Project: Smart Campus 360
Track: AI/ML • Sustainability • Internet of Things • Open Innovation

📌 Overview

Smart Campus 360 is an AI + IoT powered institutional platform designed to bring essential campus information, resource monitoring, student services, navigation, and intelligent insights into one unified digital ecosystem.

The platform addresses fragmented campus data, delayed issue detection, underused resources, and communication gaps by connecting IoT sensors, AI/ML analytics, campus maps, student services, and an administrative dashboard.

The system is designed to serve students, faculty, campus administrators, department heads, coordinators, club leaders, and event organizers.

🎯 Problem Statement

Campus data is often fragmented across different services and departments. This can lead to:

Issues being detected late

Resources being underused

Communication gaps

Limited awareness of campus services

Difficulty accessing verified campus information

Lack of centralized monitoring and analytics

Smart Campus 360 provides a centralized platform where campus information, resource intelligence, student services, and actionable insights can be accessed through a single interface.

👥 Target Users

Students

Faculty

Campus Administrators

Department Heads

Coordinators

Club Leaders

Event Organizers

✨ Core Features

🤖 AI + IoT Monitoring

Monitor important campus resources through connected sensors and data sources:

Electricity usage

Water meters

Smart bins

Temperature

Air quality

Environmental conditions

📊 AI Analytics

The analytics layer provides:

Consumption prediction

Anomaly detection

Waste classification

Resource optimization

Sustainability analytics

Smart alerts and insights

📝 Complaint Management

Users can:

Report campus issues

Upload supporting images

Track complaints

View complaint status

Administrators can review and manage reported issues.

📞 Verified Contact Directory

Provides verified staff information with:

Staff contact details

Verified phone numbers

Relevant campus roles

Privacy controls

Role-based access

🏫 Club Directory

Students can discover:

Clubs

Club contacts

President and VP details

Senior members and their year/class

Club coordinators

Events and registration information

🗺️ Campus Map & Local Intelligence

Smart Campus 360 provides a Google Maps-like experience designed specifically for the college.

Users can:

Explore campus buildings and facilities

Locate canteens, cafés, sports facilities, hostels, labs, and libraries

View live information for campus locations

Find multiple routes between campus points

Choose shortest, accessible, or landmark-based routes

Get walking distance and ETA

Receive turn-by-turn guidance

View live route closures

Search useful places within a maximum 50 km radius

The neighbourhood layer can include:

Hospitals

Pharmacies

Banks

Food outlets

Transport

Stores

PGs

🍽️ Food & Canteen Explorer

For campus food outlets, the platform can provide:

Outlet location

Opening/timing information

Available food items

Menu and prices

Availability information

📚 Library Explorer

Students can search the complete college book inventory by section, including categories such as:

Biotechnology

Programming

Competitive

Novels

Chemical Engineering

The system can also show:

Shelf/section

Book availability

Teacher-in-charge

🎓 Hackathon & Event Discovery

Students can discover:

College events

Hackathons

Registration information

Event dates

Organizers

Contact information

🖥️ Student Portal & Admin Dashboard

The platform provides separate interfaces for students and administrators.

Student Portal

Campus services

Maps

Clubs

Events

Food

Library

Complaints

Local information

Admin Dashboard

Resource monitoring

IoT data

Alerts

Complaint management

Analytics

Campus information management

🏗️ System Architecture

                    ┌─────────────────────┐
                    │    IoT Sensors      │
                    │ Electricity / Water │
                    │ Waste / Environment │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │   MQTT / API Layer  │
                    │ Data & Protocol Mgmt │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │    Backend Server   │
                    │ Business Logic      │
                    │ Processing & APIs    │
                    └──────────┬──────────┘
                               │
                 ┌─────────────┴─────────────┐
                 ▼                           ▼
       ┌──────────────────┐       ┌──────────────────┐
       │ AI / ML Engine   │       │ Database         │
       │ Prediction       │       │ PostgreSQL /     │
       │ Anomaly Detection│       │ MongoDB          │
       │ Classification   │       │ Secure Storage   │
       └────────┬─────────┘       └────────┬─────────┘
                │                          │
                └────────────┬─────────────┘
                             ▼
                   ┌─────────────────────┐
                   │   Web Dashboard     │
                   │ Students / Admin    │
                   └─────────────────────┘

🛠️ Technology Stack

Layer

Technologies

Frontend

React

Backend

Node.js / Express

Database

PostgreSQL / MongoDB

Messaging

MQTT

AI/ML

Python, TensorFlow, scikit-learn

IoT

Electricity, water, waste & environmental sensors

Authentication

Authentication + role-based access

Cloud

Cloud deployment platforms

Storage

Image storage / cloud storage

Maps

Interactive campus mapping and routing

🧩 Key Components

Frontend

The React-based interface provides monitoring and management screens for students and administrators.

Backend

Node.js/Express handles APIs, business logic, processing, authentication, and communication between platform components.

Database

PostgreSQL or MongoDB stores campus information, users, complaints, resources, events, clubs, library information, and analytics data.

Messaging Layer

MQTT provides communication between IoT devices and the application layer.

AI/ML Engine

Python-based AI/ML services use TensorFlow and scikit-learn for analytics, prediction, anomaly detection, and classification.

Cloud Services

Cloud deployment and storage support scalable access, image storage, and reduced infrastructure requirements.

🔐 Privacy & Security

The platform includes:

Authentication

Role-based access control

Verified contact information

Privacy-aware contact management

Admin review and validation

Human verification for important AI-generated alerts

🚀 Roadmap

Phase 01 — Foundation

Campus database

IoT integration

Maps and facilities

User management

Basic dashboard

Phase 02 — Intelligence

AI analytics

Anomaly detection

Resource prediction

Smart alerts

Intelligent insights

Phase 03 — Student Layer

College maps

Smart routing

Food menus

Library explorer

Student services

Campus Connect

Phase 04 — Smart Campus

Unified AI-powered campus platform

Sustainability intelligence

Neighbourhood insights

Advanced resource optimization

Smart decision support

💡 Campus Connect

Campus Connect is the student-focused innovation layer of Smart Campus 360.

It integrates:

College maps and multiple campus routes

Food outlets, menus and prices

Library books, sections and teachers

Authorities, clubs and coordinators

Events and student opportunities

Hackathons

50 km neighbourhood information

Institution-verified contacts and information

The goal is to provide one digital campus layer for everyday student and institutional needs.

⚙️ Feasibility

Smart Campus 360 is designed using proven AI, IoT, and web technologies.

Key feasibility points:

Centralized database for campus information

Simple interface for users

Modular architecture for future features

Cloud deployment to reduce infrastructure and maintenance costs

Existing IoT protocols and AI/ML technologies can support implementation

⚠️ Risks & Mitigation

Risk

Mitigation

Map data gaps

Use verified campus maps

Sensor availability

Use simulated data initially

Data accuracy

Add validation and admin review

Large campus data

Use modular database architecture

AI prediction errors

Keep human verification for alerts

🌟 Unique Selling Proposition

Smart Campus 360 creates a unified platform connecting:

Resource Intelligence + Campus Navigation + Student Engagement

It combines proactive alerts, verified information, campus services, clubs, events, navigation, and sustainability analytics within a single institutional ecosystem.

💼 Business Model

Potential revenue model:

Subscription / annual institutional license

Optional analytics and support tiers

Implementation and integration fees

👨‍💻 Team — APEX DEVS

Member

Responsibility

Ananya Bansal

AI/ML & Data Analytics Lead

Arushi Shrikar

Frontend & Student Portal Lead

Akshay Singhal

Backend & Database Lead

Anurag Saini

IoT & System Integration Lead

📚 References

The project proposal references:

Official MQTT documentation

React documentation

Node.js documentation

TensorFlow documentation

scikit-learn documentation

PostgreSQL / MongoDB documentation

Cloud IoT platforms

Sustainability and smart-campus research papers

Open datasets

Relevant smart-campus case studies

🎥 Project Explanation

A project explanation video can be added here:

[Add Project Video Link]

📄 Project Summary

Smart Campus 360 is an AI + IoT powered smart-campus platform that combines real-time resource monitoring, AI-driven analytics, campus navigation, complaints, verified contacts, clubs, events, library services, food information, and neighbourhood intelligence. Its modular architecture enables institutions to begin with campus databases and IoT integration and progressively add AI intelligence and student-focused services.

📌 Project Vision

Empowering campuses to be safer, more connected, and resource-efficient through innovative AI + IoT solutions.

⭐ Status

Hackathon Prototype / Smart Campus Platform Concept

Future development can include real IoT hardware integration, production-grade authentication, live campus maps, advanced AI models, mobile applications, and deployment at institutional scale.
