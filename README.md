# 2026-2027-Certification-and-Project-Plan-
This repository is the outline of Certifications and projects that I plan to acquire and create during the 2026 Summer.

## School Projects
  1. Undergraduate Research (Dynamic Resource Allocation in Cloud Distribution Systems)
       
    Thesis: A hybrid dynamic resource allocation framework
    combining predictive deep-learning schedulers for
    baseline demand with Online Convex Optimization
    for real-time drift correction achieves
    lower operational costs while maintaining SLA
    guarantees under non-stationary traffic

    This project is hosted on this repository:


    Current Technology Stack / Architecture: 
    - ML / Optimization: PyTorch, NumPy, SciPy
    - Cloud & Containers: Docker, FastAPI, Prometheus, Grafana
    - Traffic Testing: trafficGenerator.py

  2. Ohio Northern University Polar Robotics (Codebase restructuring from Object-Oriented Programming to Interrupt-based on Embedded Hardware)   

## Certifications

  1. AWS Certified Machine Learning Engineer Associate
  2. AWS Certified CloudOps Engineer Associate

## Personal Projects
  1. Create Personal Website
  
    This webpage will be hosted at jaydinRethmel.com
    and will be my first project of the 2026 summer.
    This webpage will include the Homepage 
    (General Summary of Bio, Education, Certification, Projects, and Experience),
    the Bio page, Education, Certification, Projects, and Experience
  
    Current Technology Stack / Architecture:
    - Frontend Framework: Angular
    - Hosting & CI/CD: AWS Amplify Hosting
    - CDN & Caching: Amazon CloudFront
    - SSL / HTTPS: AWS Certificate Manager
  
  2. Real - Time Multimodal Content Safety & NLP Analytics Pipeline

    An automated system that ingest user text and images
    (especially product review or social media posts)
    steams them through an ETL pipline, processes them
    with quantized Deep Learning models (Sentiment, Toxicity, image Classification),
    and serves interactive visual analytics
    throguh an Angular web dashboard

    Current Technology Stack / Architecture:
      - Frontend Framework: Angular
          - Hosted On: Vercel
      - API Gateway: FastAPI
          - Hosted On: Hugging Face Spaces
      - Data Orchestration: Prefect
      - Database: PostgreSQL + AWS S3
          - Hosted On: Supabase + AWS S3
      - ML Models: ONNX Runtime / Hugging Face Transformers
          - Hosted On: Hugging Face Docker Container

    System Architecture:
      ┌────────────────────────────────────────────────────────┐
      │        ANGULAR PORTFOLIO SITE (Vercel / Netlify)       │
      │  - Real-time prediction dashboard                      │
      │  - Reactive forms (RxJS) & Chart.js data visuals       │
      └───────────────────────────┬────────────────────────────┘
                                  │ (REST / WebSocket)
                                  ▼
      ┌────────────────────────────────────────────────────────┐
      │        FASTAPI / DOCKER BACKEND (Hugging Face)         │
      │  - Heavy inference (PyTorch/ONNX with 16GB RAM)        │
      │  - Input validation, pre-processing, post-processing   │
      └─────────────┬────────────────────────────┬─────────────┘
                    │                            │
                    ▼                            ▼
      ┌──────────────────────────┐   ┌──────────────────────────┐
      │  DATABASE (Supabase)     │   │   STORAGE (AWS S3)       │
      │  - Raw/Processed Logs    │   │  - Saved Image Artifacts │
      │  - Data Engineering Sink │   │  - Model Metadata        │
      └──────────────────────────┘   └──────────────────────────┘

