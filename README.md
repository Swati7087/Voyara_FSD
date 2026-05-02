<div align="center">

#  Voyara
## Your Intelligent, End-to-End Local Travel Companion

> *Experience the world your way. Plan the journey, not just the bookings.*

</div>


##  The Vision: Revolutionizing Travel Planning

Currently, travel planning is a fragmented, stressful mess of open tabs—flights here, hotels there, and generic "top 10 things to do" lists that offer no real local insight. Most platforms stop once the flight is booked.

**Voyara changes the paradigm.** We are not just another booking engine; we are an intelligent, interactive platform that acts as your **personal local tour guide** for unknown cities.

Voyara is an **itinerary builder** that gamifies the entire planning process, taking users from an initial travel idea to a **fully structured, day-wise, budgeted, and actionable itinerary**. Our core mission is to surface local activities and meaningful experiences and integrate them seamlessly into a single planning flow.


## Problem Statement

Travel planning today is highly fragmented. Users depend on multiple platforms for:
- Flights and transport  
- Accommodation  
- Local attractions and activities  
- Budget planning  
- Daily scheduling  

This results in:
- Disorganized plans  
- No clear day-wise execution  
- Poor budget visibility  
- Generic tourist experiences  

Most platforms stop at bookings and fail to support the **actual travel experience**.


## Proposed Solution

Voyara provides an end-to-end **itinerary building platform** that converts scattered travel ideas into a single visual and structured journey.

Voyara enables users to:
- Plan trips day-by-day using an interactive timeline  
- Discover local experiences instead of generic tourist lists  
- Track time and budget together  
- Receive intelligent AI assistance while staying in full control  

---

<div>

##  Live Demo && Resources

###  **[Click Here to Launch Voyara Web Live](https://voyara.onrender.com)**

###  Technical Documentation
Detailed system documentation is organized inside the repository:
- **[Docs Folder](./docs/)**
  - **[Flowchart Explanation](./docs/FLOWCHART.md)**
  - **[Wireframes & DFDs](./docs/WIREFRAME_AND_DFD.md)**
- **[Assets Folder](./assets/)**
  - Flowcharts
  - Data Flow Diagrams (DFDs)
  - Database Schema
  - UI Wireframes

  </div>

##  Key Differentiators (Why Voyara)

Voyara solves the hardest part of travel:

> **“What do I do when I get there?”**

###  1. Interactive Journey Timeline

Instead of static lists, Voyara uses a **visual timeline** that represents:
- Travel legs  
- Day-wise activity blocks (morning / afternoon / night)  
- Budget and time distribution  

**Impact:** Planning feels intuitive and engaging instead of overwhelming.


### Example: 3-Day Paris Trip in Voyara

- **Day 1:** Eiffel Tower → Louvre → Seine Cruise  
   Estimated Budget: €120  

- **Day 2:** Montmartre → Local cafés → Street exploration  
   Estimated Budget: €90  

- **Day 3:** Versailles Day Trip  
   Estimated Budget: €150  

All of this appears in **one structured timeline**, not scattered notes.

---

###  2. Local-First Discovery Engine

Voyara prioritizes **local activities and experiences** instead of generic tourist traps.

**Impact:** Users explore cities like locals, not checklist tourists.


###  3. Vega – Context-Aware AI Assistant

Vega is Voyara’s intelligent **assistive AI** that helps users plan better without taking control away.

#### Design Principles
- User-in-the-loop (no autonomous actions)  
- Suggest, don’t decide  
- Context-aware recommendations  
- Explainable reasoning  
- Fail-safe fallback  

#### What Vega Does
- Suggests activities for specific days  
- Helps optimize time and budget  
- Explains *why* a suggestion fits the itinerary  

#### What Vega Cannot Do
- Modify itineraries automatically  
- Perform bookings  
- Trigger background actions  
- Write to databases  

Vega fully complies with hackathon AI rules and remains **strictly assistive**.


###  4. One-Click Budget Export

Voyara converts the entire itinerary into a structured **Excel budget sheet**, including:
- Transport costs  
- Activity costs  
- Daily breakdown  

**Impact:** Offline-ready and practical for real travel use.


## Data Flow & System Design

Voyara follows a clean and modular architecture.

- User inputs flow through authentication and trip planning modules  
- Timeline data is processed centrally  
- Vega AI receives **read-only contextual data**  
- All suggestions return to the UI for **explicit user approval**  

 Detailed **DFDs, Flowcharts, and Wireframes** are available inside `/docs` and `/assets`.


##  Tech Stack: Hybrid & Scalable

| Component | Technology | Purpose |
|---------|-----------|---------|
| **Frontend (Web)** | React + TypeScript | Interactive UI & timeline |
| **Mobile Core** | Kotlin Multiplatform (KMP) | Shared business logic |
| **Backend API** | Node.js + TypeScript | Auth, trip management |
| **AI Service Layer** | FastAPI (Python) | Vega AI inference layer |
| **AI Engine** | GenAI / LLMs | Context-aware suggestions |
| **Database** | PostgreSQL | Relational data storage |
| **Legacy Modules** | Java | Stability & integration |


<div align="center">

*TEAM MEMBERS 
**- SWATI** 
**- PRAKHAR**
**- LOVISH***

</div>
