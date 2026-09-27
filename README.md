#Zira3i AI (طبيب زراعي ذكي) - Project Architecture & Technical Specification

#1. Executive Summary

Zira3i AI is a production-ready, multi-service Agricultural AI Doctor platform built for a 7-hour hackathon. It bridges the gap between advanced artificial intelligence and local agricultural needs in Algeria and North Africa, focusing on strategic crops (potatoes, tomatoes, and olives). The application rejects the monolithic chat interface pattern in favor of a specialized, high-performance Multi-Service Architecture wrapped in a futuristic cyber-organic UI.

#2. Technical Stack

Frontend: Flutter (Cross-platform: Android, iOS, Web)

Backend: Python (FastAPI / Flask wrapper)

AI Engine: Google Gemini API (Multimodal vision + text generation)

Key Packages: image_picker (field photography), flutter_markdown (structured AI responses), flutter_animate (micro-interactions and smooth transitions)

Design Philosophy: Minimalist Claude-inspired foundation fused with cyber-organic glassmorphic elements and high-tech telemetry.

#3. System Architecture & Component Breakdown

[ Flutter Frontend (Multi-Service Dashboard) ]
       │
       ├──> 1. Disease Diagnosis Module (Multimodal Vision + Confidence Scores)
       ├──> 2. Water Advisor Module (Soil/Crop Irrigation Analytics)
       ├──> 3. Quantum-Inspired Optimization Module (Resource Distribution)
       └──> 4. Safety & Guidance Module (Agronomic Compliance & Disclaimers)
       │
       ▼ (REST API / JSON payloads)
[ Python Backend Middleware ]
       │
       ▼
[ Google Gemini API Engine ]




Module Specifications:

Dashboard & Glassmorphic Landing (welcome_screen.dart / dashboard_screen.dart):

Features a transparent, color-gradient glassmorphic navigation bar.

Real-time agritech micro-widgets displaying local telemetry (soil moisture, temperature, satellite health indices).

Quantum-organic custom branding logo combining organic leaves with digital AI nodes.

Disease Diagnosis Service (diagnosis_page.dart):

Instant camera and gallery integration via image_picker.

Markdown-enabled rich text rendering for symptoms, treatments, and prevention.

Confidence Score Badge Component: Quantifies AI certainty (e.g., $\text{Confidence} = 94.5\%$).

Alternative Hypothesis Section: Secondary differential diagnoses to prevent misapplication of treatments.

Water Advisor Service (water_advisor_page.dart):

Tailored irrigation schedules and water volume calculations per crop lifecycle stage.

Quantum Optimization Service (quantum_optimization_page.dart):

Implements quantum-inspired resource allocation models to optimize water distribution under scarcity constraints. Mathematically modeled as:

$$\min \sum_{i=1}^{n} (W_{\text{demand}, i} - W_{\text{allocated}, i})^2 \quad \text{subject to} \quad \sum W_{\text{allocated}} \le W_{\text{total}}$$

Safety & Guidance Banner (safety_disclaimer_banner.dart):

Mandatory safety notice preventing reckless pesticide dosing and directing farmers toward certified agronomists.

#4. Design System & Styling Rules

Color Palette:

Background: Warm Neutral (#F7F7F5) / Dark Cyber Fusion (#121814)

Primary Text: Deep Charcoal (#2D2D2D)

Accents: Muted Forest Green (#38A169) & Electric Mint (#4FD1C5)

Layout & Motion:

Staggered physics-based entry animations (Curves.easeInOutCubic).

Holographic micro-tilt cards with reactive glass borders.

#5. Regional Context & Strategic Crops

Primary Focus Crops:

طماطم (Tomatoes): Early/Late Blight detection, leaf curl analysis.

بطاطا (Potatoes): Fungal tuber rots, leaf spot management.

زيتون (Olives): Peacock spot (œil de paon) detection and supplementary irrigation planning.
