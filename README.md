# kota-hub
Kota Hub is a digital nervous system designed for the South African township economy. It bridges the gap between informal food vendors (Kota shops/spaza shops) and local customers through a sustainable, bicycle-powered delivery network.

🍔 Kota Hub: Hyper-Local Bicycle Delivery Ecosystem

Kota Hub is a digital nervous system designed for the South African township economy. It bridges the gap between informal food vendors (Kota shops/spaza shops) and local customers through a sustainable, bicycle-powered delivery network.
🚀 The Problem

    Logistics Gap: Global delivery giants often bypass townships or charge fees higher than the meal itself.

    Data Blindness: Small vendors lack digital records of sales, stock, and high-performing menu items, making growth difficult.

    Unemployment: High local unemployment despite a booming informal food economy.

💡 The Solution

A lightweight, mobile-first platform that:

    Digitalizes Vendors: Provides weekly business reports and inventory tracking.

    Orchestrates Logistics: Dispatches local "Hub Runners" on bicycles for cost-effective, last-mile delivery.

    Enhances Trust: Real-time tracking and secure PIN verification for every order.

🛠 Tech Stack
Backend (The Engine)

    Language: Python 3.10+ (Focused on high-performance asynchronous logic).

    Framework: FastAPI (Chosen for speed and automatic Swagger documentation).

    Database: PostgreSQL with PostGIS for location-based spatial queries.

    Task Queue: Redis for managing real-time delivery notifications.

Frontend (The User Experience)

    Framework: Flutter (Cross-platform for Android/iOS).

    Aesthetics: Glassmorphic UI elements with a Soft Rose color palette for a premium local feel.

DevOps (The Infrastructure)

    Containerization: Docker for consistent environment deployment.

    CI/CD: GitHub Actions for automated testing and linting.

    Cloud: Google Cloud Platform (GCP) utilizing Cloud Run for serverless scaling.

🏗 System Architecture

The system operates as a System Orchestrator, managing three distinct user flows:

    Vendor Module: Menu management, stock alerts, and weekly performance analytics.

    Runner Module: Geofenced order dispatching and route optimization for bicycles.

    Customer Module: Lite, data-efficient ordering interface with live order status.

🔧 Getting Started
Prerequisites

    Python 3.10+

    Docker & Docker Compose

    PostgreSQL
