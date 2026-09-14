# PRANAV – Intelligent Healthcare Resource Network

### Connecting Care. Protecting Life.

PRANAV is a modern healthcare coordination platform designed to help people, donors, blood centres, healthcare facilities, and emergency coordinators connect faster during critical blood-resource requirements.

The platform focuses on intelligent coordination, resource discovery, request tracking, accessibility, and healthcare information support.

---

## 🚨 The Problem

During a blood emergency, patients and their families may struggle to:

- Find relevant blood resources quickly
- Identify nearby blood centres and facilities
- Coordinate with potential donors
- Track the status of an emergency request
- Understand the next steps during a stressful situation
- Access healthcare information in simple language

Existing systems can provide important information, but the emergency journey can still involve multiple disconnected steps.

---

## 💡 Our Solution

PRANAV creates a unified coordination layer around the emergency blood-resource journey:

**Emergency Request → Requirement Analysis → Smart Matching → Resource Discovery → Verification → Coordination → Tracking → Resolution**

PRANAV is designed to make this journey simpler, faster, more accessible, and easier to coordinate.

> PRANAV does not guarantee blood availability. Potential matches and resource information must be verified through authorised healthcare or blood-centre channels.

---

## ✨ Key Features

### 🩸 Emergency Blood Coordination
Create an emergency request with:

- Blood group
- Blood component
- Required units
- Urgency level
- City / District
- Healthcare facility
- Required date and time
- Contact method
- Additional notes

Each request receives a unique **PRANAV Request ID**.

### 🔎 Smart Resource Matching

PRANAV can organise potential resources based on:

- Blood group
- Component
- Location
- Resource type
- Proximity
- Availability information
- Urgency
- Last updated status

Potential resources are clearly labelled as:

**Potential Match — Verification Required**

### 📍 Resource Discovery

Users can explore blood centres, healthcare facilities, camps, and other relevant resources through a structured, map-ready interface.

### 🤝 Donor Network

A privacy-first donor coordination architecture helps connect potential donors without publicly exposing sensitive personal information.

Final donor eligibility and donation decisions remain with authorised healthcare professionals / blood centres.

### 🤖 PRANAV AI Assistant

The AI assistant is designed to provide:

- Emergency guidance
- Blood-resource navigation
- Blood education
- Request tracking assistance
- Website navigation
- Prescription feature navigation
- Hindi / English / Hinglish interaction
- Simple-language guidance

The assistant does **not** diagnose diseases or independently prescribe medicines.

### 💊 Prescription Intelligence

Users can upload a prescription for structured information extraction.

The system can organise visible information such as:

- Medicine name
- Strength
- Dosage form
- Frequency
- Duration
- Quantity
- Instructions
- Manufacturing date
- Expiry date
- Batch number
- Manufacturer

PRANAV does not independently calculate or prescribe medicine doses. Unclear information should always be confirmed with a doctor or pharmacist.

### 📊 Healthcare Dashboard

A facility-oriented dashboard can present:

- Emergency requests
- Potential matches
- Verification queue
- Active coordination
- Resolved requests
- Demand trends
- District-level demand
- Component demand
- Response trends
- Resolution metrics
- Prototype heatmaps

Analytics are presented as **decision-support estimates** where applicable.

### 🧓 Easy Mode

A simplified interface designed for:

- Elderly users
- Low-literacy users
- Users under stress
- Users who prefer large buttons and simple instructions

### 📚 Blood Education

Educational content covering:

- Blood groups
- Red blood cells
- Platelets
- Plasma
- Blood donation basics
- Emergency awareness
- Verification
- Common misconceptions

### 🏥 Blood Donation Camps

A structured camp-discovery interface helps users explore available camp information.

Demo data is clearly identified as **Prototype / Demo Data**.

### 📦 Request Tracking

Users can enter their **PRANAV Request ID** and view the coordination timeline and current status.

---

## 🧭 Emergency Mode

PRANAV provides a simplified emergency interface with quick actions:

- 🩸 Need Blood
- 🔎 Find Resource
- 🤖 Talk to PRANAV
- 💊 Analyse Prescription
- 🏥 Contact Facility
- 📦 Track Request

---

## 🎨 Design Philosophy

PRANAV follows a premium medical-technology visual language using:

- Medical mint / light green
- Soft light red / rose
- Deep crimson
- White
- Charcoal
- Subtle grey

The interface is designed to feel:

**Professional • Trustworthy • Fast • Accessible • Futuristic**

---

## ⚙️ Technology

PRANAV is designed as a modular web platform using:

- HTML5
- CSS3
- JavaScript
- JSON-based demo data
- Progressive Web App architecture
- Responsive design
- Accessibility-focused UI
- Service Worker
- Modular JavaScript architecture

The current implementation is designed as a frontend prototype and can be extended with secure backend services and verified healthcare data sources.

---

## 📁 Project Structure

```text
PRANAV/
│
├── index.html
├── emergency.html
├── blood-request.html
├── find-blood.html
├── donor.html
├── camps.html
├── blood-education.html
├── assistant.html
├── prescription.html
├── medicine.html
├── tracking.html
├── dashboard.html
├── easy-mode.html
├── about.html
├── privacy.html
│
├── css/
│   ├── style.css
│   ├── responsive.css
│   ├── animations.css
│   ├── assistant.css
│   ├── prescription.css
│   └── dashboard.css
│
├── js/
│   ├── loader.js
│   ├── animations.js
│   ├── app.js
│   ├── emergency.js
│   ├── request.js
│   ├── tracking.js
│   ├── donor.js
│   ├── search.js
│   ├── dashboard.js
│   ├── easy-mode.js
│   ├── accessibility.js
│   ├── assistant.js
│   ├── prescription.js
│   └── medicine.js
│
├── data/
│   ├── blood-centres.json
│   ├── camps.json
│   └── demo-data.json
│
├── manifest.json
└── sw.js
