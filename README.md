# FelpsXP Ecosystem

## Overview

**FelpsXP Ecosystem** is a personal technology ecosystem designed to build, operate, and scale real-world software products.

The ecosystem combines personal projects, software plataforms, automation systems, and experimental technologies into a unified archtecture.

The main goals of this ecosystem are:

- Build real software products
- Develop production-level engineering skills
- Create a strong international portfolio
- Explore automation, AI, and hardware integration
- Launch scalable SaaS plataforms in the fucture

This repository contains the core structure of the ecosystem and its applications.

---

# Ecosystem Projects

The ecosystem is composed of several interconnected applications.

## Farm System

A **3D printing farm management system** responsible for controlling printers, managing production, tracking inventory, and monitoring operations.

Features:

- Printer monitoring 
- Print job management 
- Production automation
- Inventory tracking 
- Sales integration
- Analytics dashboards 

The system is designed to scale from a **single home printer to a full production farm.**

---

## PrintLab Store

An e-commerce plataform where users can:

- Browse products
- Purchase printed items
- Access exclusive offers
- Be redirected to marketplaces when necessary

This plataform integrates directly with the Farm System production pipeline.

---

## FelpsXP Website 

The official website and personal hub.

Purpose:

- Professional portfolio
- Content publishing 
- Projects showcase
- Blog and documentation
- Personal brand

---

# High-Level Architecture

The ecosystem follows a modular architecture.

```
FelpsXP Ecosystem 
    |
    |- Farm System
        |- Frontend Dashboard 
        |- Backend API
        |- Printer Agents
        |- Automation Workers
    |
    |- PrintLab Store
        |- E-commerce platform
    |
    |- FelpsXP Website
        |- Portfolio and content plataform
```

Each application can evolve independently while sharing internal packages and infrastructure.

---

# Technology Stack

The ecosystem uses modern technologies aligned with standards.

| Frontend
    
    - Next.js
    - TypeScript
    - Tailwind CSS
    - Modern UI components libraries

| Backend

    - Python
    - FastAPI

| Database

    - PostgreSQL

| Infrastructure

    - Docker
    - Container-based architecture

| Automation

    - Python workers
    - Quere systems 
    - Scheduled tasks

| Printer Integration

    - OctoPrint
    - Klipper

---

# Repository Sctructure

```
felpsxp-ecosystem
    |
    |- apps
        |- farm-system
        |- printlab-store
        |- felpsxp-site
    |
    |- packages
        |- ui
        |- database
        |- auth
        |- shared-types
    |
    |- docs
        |- architecture
        |- database
        |- api
        |- setup
        |- roadmap
    |
    |- infra
        |- docker
        |- scripts
```

---

# Documentation

Project documentation is available in the ```/docs``` directory.

Topics include:

    - Architecture
    - API specifications
    - Database schema
    - Development setup
    - infrastructure
    - Roadmap
---

# Developement Goals

This ecosystem is build with several long-term goals:

    - Develop high-level engineering skills
    - Build production-ready software
    - Create reusable systeams
    - Build SaaS-ready infrastructure
    - Explore automation and AI

---

# Roadmap

Future development includes:

    - Advanced automation systems 
    - AI-assistent production
    - Marktplace integrations
    - Mult-farm support 
    - SaaS version of the farm system
    
---

# Author 

Felipe Luis Rodrigues Sousa

Software Engineer focused on building scalable system, automation, and modern web applications.

---

# Licence 

This project is currently private and under active development.