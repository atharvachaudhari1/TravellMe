# ARKA -- AI Travel Planner & Disruption Recovery Engine ✈️

> **Transforming fragile travel itineraries into resilient journeys.**

AI-powered travel planning combined with a deterministic disruption
recovery engine for flights, trains, hotels, transfers, activities, and
severe weather disruptions.

------------------------------------------------------------------------

## 🏆 HackCelestial 3.0

**Team Name:** 🚀 Arka\
**Problem Statement:** PS2 --- Travel Disruption Recovery Engine:
Intelligent Travel Resilience\
**Team Leader:** Bhakti Nimaj\
**Email:** bhaktinimaj94@gmail.com

------------------------------------------------------------------------

## 🚀 Live Demo

🌐 **[arkaa.online/travell](https://arkaa.online/travell)**

Experience the ARKA travel planning and disruption recovery system live.

------------------------------------------------------------------------

## 🎥 Demo Video

▶️ **[Watch ARKA in Action](https://youtu.be/bvHPdmxEpGc)**

------------------------------------------------------------------------

## 💡 About ARKA

**ARKA** is an AI-powered travel disruption recovery engine that
transforms fragile itineraries into **resilient journeys**.

It models **flights, trains, hotels, transfers, and activities as a
connected dependency graph**, detects disruptions, maps their downstream
ripple effects, and generates optimized recovery plans.

ARKA combines **deterministic optimization** with **Gemini + Groq AI**
to help travelers understand, compare, and recover from disruptions
quickly.

------------------------------------------------------------------------

# ✨ Features

-   🗺️ **AI Trip Planner**
-   🛡️ **ARKA Rescue --- Deterministic Disruption Recovery**
-   💰 **Travel Wallet**
-   ⭐ **Discover Recommendations**
-   🌐 **15+ Language Translation**
-   🚀 **TravelMe Local Travel Assistance**
-   📅 **Timeline Builder**
-   ⚠️ **Proactive Risk & Connection Warnings**
-   🔄 **One-Click Itinerary Rebuild**
-   🤖 **Gemini + Groq AI Fallback**
-   📱 **Web + Native Flutter Mobile Experience**

------------------------------------------------------------------------

# 🛡️ ARKA Rescue

ARKA Rescue represents a connected itinerary as a **dependency graph**.

``` text
Bookings → Nodes
Dependencies → Edges
```

When a disruption occurs, ARKA analyzes the graph to determine both the
**direct impact** and **downstream ripple effects** across the journey.

### Supported Disruptions

-   ✈️ Flight cancellation / delay
-   🚆 Train cancellation
-   🏨 Hotel disruption / cancellation
-   🌧️ Severe weather

### Graph Node States

``` text
SAFE
RISK
DELAYED
CANCELLED
```

------------------------------------------------------------------------

# 🔄 Recovery Engine

ARKA generates three tailored recovery plans:

### 💰 Lowest Cost

Optimizes the journey around minimizing additional travel cost.

### ⚡ Fastest Arrival

Prioritizes reaching the destination as quickly as possible.

### 🔗 Maximum Continuity

Prioritizes preserving the existing itinerary, bookings, and activities.

Each option can be compared using:

-   💵 Cost
-   ⏱️ Time
-   🎯 Risk
-   🏃 Convenience
-   💸 Refunds
-   📍 Activities Preserved

------------------------------------------------------------------------

# ⚙️ How ARKA Works

``` text
Disruption Detected
        ↓
Build Dependency Graph
        ↓
Analyze Direct Impact
        ↓
Trace Downstream Ripple Effects
        ↓
Run Multi-Objective Optimization
        ↓
Generate Recovery Plans
        ↓
Compare Trade-offs
        ↓
Traveler Approval
        ↓
Rebuild Affected Itinerary
        ↓
Journey Restored
```

After approval, ARKA automatically updates the affected itinerary and
timeline while preserving unaffected parts of the journey.

------------------------------------------------------------------------

# 🧠 Core Processing Engine

### Graph-Based Modeling

``` text
Bookings → Nodes
Dependencies → Edges
```

### Ripple-Effect Analysis

Propagates disruptions through connected itinerary nodes to identify
downstream risks.

### Multi-Objective Optimization

Balances:

``` text
Cost + Time + Refunds + Risk + Activities Preserved
```

### Hybrid Decision Engine

Rules ensure recovery feasibility while AI assists with understanding
and recommendations.

### Constraint-Aware Recovery

Recovery plans consider:

-   Timing
-   Availability
-   Location
-   Booking policies
-   Traveler preferences

------------------------------------------------------------------------

# 🌟 What Makes ARKA Different?

  -----------------------------------------------------------------------
  Capability              Traditional Travel AI   🚀 ARKA
  ----------------------- ----------------------- -----------------------
  Disruption Analysis     Generic advice          Deterministic
                                                  dependency graph

  Downstream Impact       Often missed            Full ripple-effect
                                                  mapping

  Recovery Options        Single alternative      3 optimized plans

  Optimization            Limited                 Cost + Speed +
                                                  Continuity

  Trade-off Metrics       Limited                 Cost, time, risk &
                                                  activities

  Itinerary Updates       Manual / full           Granular automated
                          regeneration            updates

  AI Reliability          Single AI dependency    Gemini + Groq fallback

  Platform                Primarily web           Web + Flutter mobile

  Recovery                Manual replanning       One-click automated
                                                  rebuild
  -----------------------------------------------------------------------

------------------------------------------------------------------------

# 💎 Unique Functionality

### 1. Deterministic Graph-Based Disruption Engine

Calculates direct and downstream impacts across connected itinerary
components.

### 2. Multi-Objective Recovery Engine

Generates three recovery strategies:

-   Lowest Cost
-   Fastest Arrival
-   Maximum Continuity

### 3. Fail-Safe Dual-Engine AI

Uses Google Gemini Flash as the primary AI engine with Groq as the
automatic fallback.

### 4. Granular Smart Updates

Only affected itinerary segments are modified instead of regenerating
the entire journey.

### 5. Web + Native Mobile Experience

A unified backend powers both the web application and Flutter mobile
experience.

### 6. Proactive Risk & Connection Warnings

Identifies at-risk connections and activities before they become larger
problems.

### 7. Policy-Aware Recovery

Considers timing, availability, cost, refund policies, and booking
constraints.

### 8. Travel Resilience Toolkit

Includes Travel Wallet, TravelMe, multilingual assistance, and
emergency/SOS support.

------------------------------------------------------------------------

# 🏗️ Architecture

``` text
┌─────────────────────────────────────────────┐
│             PRESENTATION LAYER              │
│                                             │
│     Web SPA              Flutter Mobile     │
│   HTML/CSS/JS             Native App        │
└──────────────────────┬──────────────────────┘
                       │
                 HTTP / REST API
                       │
┌──────────────────────▼──────────────────────┐
│          ARKA RESILIENCE BACKEND            │
│                                             │
│  Dependency Graph + Recovery Engine         │
│  Ripple-Effect Analyzer                     │
│  Multi-Objective Optimizer                  │
│  Constraint-Aware Recovery                  │
│                                             │
│  Dual-Model Resilient AI Proxy              │
└───────────────┬─────────────────┬───────────┘
                │                 │
        Primary AI           Automatic Fallback
                │                 │
        Google Gemini            Groq
```

------------------------------------------------------------------------

# 🛠️ Tech Stack

## Frontend

-   HTML5
-   CSS3
-   Vanilla JavaScript
-   Single Page Application
-   Canvas / Interactive Maps

## Backend

-   Node.js
-   Express.js
-   REST API
-   CORS
-   Environment-based configuration

## AI

-   Google Gemini Flash
-   Groq
-   GPT-OSS
-   Qwen
-   Compound

## Mobile

-   Flutter
-   Dart
-   Native Android experience
-   Offline itinerary & timeline cache

## Maps & Geolocation

-   OpenStreetMap
-   Leaflet
-   Google Maps
-   W3C Geolocation API
-   Flutter Map

## Deployment

-   Vercel
-   Render
-   AWS

------------------------------------------------------------------------

# 🔌 Rescue API

  -----------------------------------------------------------------------
  Endpoint                            Purpose
  ----------------------------------- -----------------------------------
  `GET /api/rescue/scenarios`         Returns available disruption
                                      simulations

  `POST /api/rescue/analyze`          Returns graph, impact, scores &
                                      recovery plans

  `POST /api/rescue/apply`            Validates selected plan and
                                      restores trip health
  -----------------------------------------------------------------------

### Example Request

``` json
{
  "scenario": "flight_delayed",
  "preferences": {
    "priority": "continuity"
  }
}
```

------------------------------------------------------------------------

# 📁 Project Structure

``` text
ARKA/
├── frontend/
│   └── Web application
│
├── backend/
│   └── API proxy + same-origin web hosting
│
└── mobile-app/
    └── Flutter mobile experience
```

------------------------------------------------------------------------

# 🔬 Recovery Pipeline

``` text
Travel Bookings
      ↓
Itinerary Parser
      ↓
Dependency Graph
      ↓
Impact Analyzer
      ↓
Recovery Optimizer
      ↓
Itinerary Rebuilder
      ↓
Updated Timeline
```

------------------------------------------------------------------------

# 🎯 Problem → Solution

### Problem

Travel disruptions rarely affect only one booking.

A delayed flight can cause:

``` text
Flight Delay
     ↓
Missed Transfer
     ↓
Late Hotel Check-in
     ↓
Missed Activity
     ↓
Additional Cost
```

Traditional travel systems often provide an alert or a single
alternative without mapping the complete downstream impact.

### ARKA Solution

ARKA connects the entire itinerary into a dependency graph, traces the
ripple effects, evaluates constraints, and provides multiple optimized
recovery strategies.

``` text
Disruption
     ↓
Impact Mapping
     ↓
Risk Analysis
     ↓
Optimization
     ↓
Recovery Options
     ↓
Traveler Approval
     ↓
Automated Rebuild
```

------------------------------------------------------------------------

# 🔗 Project Links

🌐 **Live Demo:**\
https://arkaa.online/travell

🎥 **Demo Video:**\
https://youtu.be/bvHPdmxEpGc

💻 **GitHub Repository:**\
https://github.com/atharvachaudhari1/travell.git

------------------------------------------------------------------------

# 👥 Team

## 🚀 Team Arka

**Team Leader:** Bhakti Nimaj

**Email:** bhaktinimaj94@gmail.com

------------------------------------------------------------------------

# 🏆 HackCelestial 3.0

**Mahatma Education Society's Pillai University**

### PS2 --- Travel Disruption Recovery Engine

### **Intelligent Travel Resilience**

> **ARKA --- From Disruption to Recovery.** ✈️🛡️
