# VisionDesk AI

AI-powered workplace safety intelligence platform combining **Computer Vision, Document Intelligence, Retrieval-Augmented Generation (RAG), Large Language Models (LLMs), and Analytics** for PPE compliance monitoring.

## Overview

VisionDesk AI is designed to improve workplace safety by combining visual PPE detection with safety-document analysis and AI-powered reasoning.

The system can detect PPE compliance from images or video, retrieve relevant safety policies, analyze safety conditions, and present the results through an integrated dashboard.

## Key Features

* **PPE Detection** using YOLOv8
* **Computer Vision** for detecting safety equipment and PPE violations
* **Document Intelligence** for processing safety documents
* **RAG-based Knowledge Retrieval** for finding relevant safety policies
* **LLM Integration** for generating safety-related insights
* **AI Agent** for coordinating different components
* **Safety Reports** for summarizing detected violations
* **Dashboard** for presenting safety information and results
* **Data Storage** for maintaining application information

## System Workflow

```text
Input Image / Video
        ↓
   PPE Detection
     (YOLOv8)
        ↓
  Detect Compliance
        ↓
 Retrieve Relevant
   Safety Policy
       (RAG)
        ↓
   LLM Analysis
        ↓
 Safety Decision /
     Insight
        ↓
    Dashboard
        ↓
 Safety Report
```

## Project Architecture

```text
VisionDesk AI
│
├── Milestone 1
│   └── PPE Detection / Computer Vision
│
├── Document Intelligence (Milestone 2)
│   └── Safety Document Processing
│
├── Multimodal RAG + Agent (Milestone 3)
│   ├── RAG
│   ├── Knowledge Retrieval
│   ├── LLM
│   └── AI Agent
│
└── Milestone 4
    ├── Final Integration
    ├── Dashboard
    ├── Storage
    └── Report Generation
```

## Milestones

### Milestone 1 – PPE Detection

Implementation of computer vision-based PPE detection using YOLOv8.

The system identifies safety equipment and PPE violations such as:

* Helmet
* Gloves
* Safety vest
* Boots
* Goggles
* Missing PPE

### Milestone 2 – Document Intelligence

Processes safety-related documents and extracts useful information that can be used by the application.

This milestone establishes the document processing pipeline required for safety-policy analysis.

### Milestone 3 – Multimodal RAG + Agent

Combines retrieved safety-document information with computer vision results.

The system can use detected violations such as a missing helmet to retrieve the relevant safety policy and use an LLM to generate an appropriate safety analysis.

### Milestone 4 – Final Integration

Integrates the components developed throughout the previous milestones into a unified application.

This milestone includes:

* Dashboard
* Data storage
* Safety report generation
* Integration of PPE detection, RAG, LLM, and analytics components

## Technologies Used

* **Python**
* **YOLOv8 / Ultralytics**
* **OpenCV**
* **Streamlit**
* **ChromaDB**
* **RAG**
* **Large Language Models (LLMs)**
* **Google Gemini**
* **PyMuPDF**
* **Git & GitHub**

## Repository Structure

```text
VisionDesk/
│
├── README.md
│
├── Milestone 1/
│
├── Document Intelligence (Milestone 2)/
│
├── Multimodal RAG + Agent (Milestone 3)/
│
└── Milestone 4/
```

## Team Project

VisionDesk AI was developed as a collaborative project under the **VisionStorm4** GitHub organization.

## Purpose

The goal of VisionDesk AI is to provide an intelligent workplace safety platform that combines visual monitoring with safety-document knowledge and AI reasoning to help identify PPE violations and provide actionable safety insights.
