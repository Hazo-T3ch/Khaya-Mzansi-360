# **Khaya-Mzansi-360**
Khaya Mzansi 360 is a South African-first digital tourism and lifestyle discovery platform that helps people find what to see, where to eat, what to experience and what is around them, while creating greater visibility and economic opportunity for local tourism businesses.

### Discover. Experience. Live South Africa.

**Khaya Mzansi 360** is a South African-first tourism, lifestyle and local discovery platform designed to make exploring the country simpler, more personal and more connected.

The project is being developed by **GeoMzansi Impact Lab** for the **Geekulcha Annual Hackathon 2026** under the **Brand New** challenge category.

> **One place to discover where to go, what to see, what to eat and what to experience across South Africa.**

---

## 🌍 The Idea

South Africa has an extraordinary variety of attractions, landscapes, food, cultures and experiences, but discovering them is often fragmented across search engines, social media, tourism websites, booking platforms and word-of-mouth recommendations.

Khaya Mzansi 360 aims to bring these experiences together.

The vision is to create a platform where a traveller can discover:

* Attractions and landmarks
* National parks and nature reserves
* Adventure activities
* Restaurants and local food
* Halaal-friendly options
* Cultural and heritage experiences
* Family outings
* Local tour guides
* Hidden and lesser-known destinations
* Events and activities
* Grocery and convenience stops
* Useful places while travelling
* Road-trip stops and experiences

Rather than only asking **"Where can I book a tour?"**, Khaya Mzansi 360 is designed around a much broader question:

### **"What can I experience around me?"**

---

## 💡 Why Khaya Mzansi 360?

Many international travel platforms perform individual parts of the travel journey well.

Khaya Mzansi 360 aims to approach tourism from a **South African perspective**, bringing together discovery, food, culture, local experiences, practical travel information and future booking functionality within one ecosystem.

The platform is intended for both:

### Travellers

South Africans and international visitors looking for relevant places and experiences.

### Local Businesses & Tourism Operators

Restaurants, guides, attractions, activity providers and smaller tourism businesses that want to become easier to discover.

The long-term objective is not simply to create another directory.

It is to create a **digital gateway to experiencing South Africa**.

---

# 🚀 Hackathon Minimum Viable Product

The hackathon will focus on developing a practical **Minimum Viable Product (MVP)** rather than attempting to build the complete long-term platform immediately.

The initial prototype is intended to demonstrate five core capabilities.

### 📍 Location-Based Discovery

Allow users to discover nearby attractions, restaurants, activities and experiences based on their current or selected location.

### 🔎 Smart Search

Allow travellers to describe what they are looking for naturally instead of relying only on traditional filters.

Example:

> *"I have four hours in Pretoria, want something outdoors under R500 and somewhere Halaal to eat afterwards."*

### 🗺️ Interactive Map

Display relevant attractions, restaurants and experiences geographically and allow users to understand what is around them.

### 📌 Destination Profiles

Each listed destination can contain information such as:

* Description
* Category
* Location
* Images
* Operating information
* Approximate pricing
* Contact details
* Directions
* Useful traveller information

### 🧭 Simple Trip Builder

Allow users to save selected places and organise them into a basic day trip or travel itinerary.

---

# 🧠 Intelligent Travel Assistance

Khaya Mzansi 360 will explore the use of intelligent search and recommendation technology to help users discover experiences based on context such as:

* Location
* Available time
* Budget
* Interests
* Food preferences
* Dietary requirements
* Travel style
* Group type

The goal is not to replace traditional browsing, but to make South African travel discovery more conversational and useful.

Example searches could include:

> **"What can we do around Durban this afternoon?"**

> **"Find family activities and Halaal restaurants near me."**

> **"Plan a scenic weekend through Mpumalanga."**

> **"What interesting places can I stop at along my route?"**

---

# 👤 Example User Journey

### 1. Open Khaya Mzansi 360

The traveller shares their location or searches for a destination.

### 2. Tell Khaya What You Want

The traveller searches by category or describes the experience they are looking for.

### 3. Discover

Khaya presents relevant attractions, food, activities and nearby experiences.

### 4. Explore

The user views destination information, images, location, estimated cost and other useful details.

### 5. Build the Day

Interesting places can be saved and arranged into a simple itinerary.

### 6. Go

The user receives location and navigation information and begins exploring.

Future versions may extend this journey into reservations, guide bookings, attraction tickets and experience payments.

---

# 👥 Intended Users

Khaya Mzansi 360 is being designed for:

* Domestic South African travellers
* International visitors
* Families
* Couples
* Solo travellers
* Backpackers
* Digital nomads
* Road-trippers
* Adventure travellers
* Food-focused travellers
* Halaal-conscious travellers
* Travellers looking for authentic local experiences

The platform can also create value for:

* Restaurants
* Tour guides
* Tourism operators
* Adventure businesses
* Attractions
* Cultural organisations
* Community tourism initiatives
* Small local businesses
* Parks and reserves

---

# 🇿🇦 South African by Design

Khaya Mzansi 360 is intended to go deeper than simply displaying well-known tourist attractions.

Future development may include greater discovery of:

* Local cuisine
* Halaal-certified and Halaal-friendly businesses
* Township tourism
* Rural destinations
* Cultural experiences
* Historical sites
* Community tourism
* Local guides
* Markets
* Independent restaurants
* Small tourism operators
* Lesser-known attractions
* Road-trip experiences

The objective is to help tourism spending reach beyond only the country's most established destinations.

---

# ⚙️ Proposed Technology Stack

The project is currently at an early development stage. The proposed architecture may evolve during the hackathon as the MVP is tested.

### Frontend

* Flutter
* React / Next.js
* Responsive Web / Progressive Web App technologies

### Backend

* Node.js
* TypeScript
* REST APIs
* Python where appropriate for data and recommendation services

### Data

* PostgreSQL
* PostGIS
* Supabase
* Structured tourism and location datasets

### Mapping & Location

* Google Maps Platform and/or Mapbox
* Geolocation
* Geocoding
* Routing
* Proximity search

### Intelligent Search

* Large Language Model integration
* Retrieval-Augmented Generation
* Semantic search
* Vector embeddings
* Recommendation logic

### Infrastructure

* Cloud hosting
* Cloud storage
* Authentication
* Git
* GitHub
* Docker where appropriate

---

# 🏗️ High-Level Architecture

```text
                    ┌───────────────────────┐
                    │       Traveller       │
                    └───────────┬───────────┘
                                │
                    ┌───────────▼───────────┐
                    │  Mobile / Web Client  │
                    └───────────┬───────────┘
                                │
                    ┌───────────▼───────────┐
                    │      Application      │
                    │         API           │
                    └───────┬───────┬───────┘
                            │       │
                ┌───────────▼─┐   ┌─▼────────────────┐
                │ PostgreSQL  │   │ Search & Travel  │
                │ + PostGIS   │   │ Recommendation   │
                └───────────┬─┘   └────────┬─────────┘
                            │              │
                     ┌──────▼──────────────▼──────┐
                     │ External Services & APIs   │
                     │ Maps • Places • Routing    │
                     └────────────────────────────┘
```

---

# 💼 Business Potential

Khaya Mzansi 360 will initially focus on proving that people find the platform useful.

Potential future revenue models include:

### Booking & Referral Commission

A small commission when users successfully book eligible tours, activities, attractions or experiences.

### Business Profiles

Businesses could maintain free listings while optional professional tools provide additional functionality, analytics or promotional capabilities.

### Reservations

Potential integration with restaurant, attraction and experience reservation systems.

### Featured Discovery

Clearly identified sponsored or promoted experiences could provide businesses with additional visibility without replacing organic recommendations.

### Strategic Partnerships

Future opportunities could include tourism organisations, accommodation providers, transport platforms and other businesses serving travellers.

---

# 📈 Go-to-Market Approach

Khaya Mzansi 360 is intended to grow progressively rather than attempting immediate national scale.

### Phase 1 — Build

Develop and validate the hackathon Minimum Viable Product.

### Phase 2 — Pilot

Populate a focused geographic area with useful listings and test the experience with real travellers.

### Phase 3 — Local Business Onboarding

Invite restaurants, attractions, guides and experience providers to verify and improve their listings.

### Phase 4 — Expand

Extend coverage to additional cities, tourism routes and provinces based on user demand and available data.

### Phase 5 — Marketplace

Introduce selected reservation and booking functionality once discovery has demonstrated sufficient value.

---

# 📊 Early Success Measures

Rather than measuring success only through downloads, the project will initially look at whether users actually find value.

Possible measures include:

* Useful searches completed
* Places discovered
* Destinations saved
* Itineraries created
* Directions initiated
* Returning users
* Verified listings
* Participating tourism businesses
* User feedback
* Recommendation relevance
* Future booking conversions

A simple early question will guide development:

> **Can Khaya help someone move from "I don't know what to do" to discovering a relevant South African experience within a few minutes?**

---

# 💰 Estimated First-Year Development & Launch

A lean first-year development and launch budget of **up to R250,000** is envisioned for progressing the project beyond the prototype stage.

This could broadly support:

* Minimum Viable Product development
* Coding and platform development
* Mapping and API integration
* Cloud infrastructure
* Tourism data collection and verification
* UI/UX development
* Testing and security
* Business onboarding
* Marketing and advertising
* Content creation
* Public launch activities
* Legal and compliance foundations
* Contingency costs

Development will remain as lean and founder-led as practical, with expenditure increasing alongside real-world validation and adoption.

---

# 👨‍💻 Project Status

> **Current Status: Early Development / Hackathon Prototype**

Khaya Mzansi 360 is currently an early-stage project idea being developed initially by its founder.

The immediate objective is to use the Geekulcha hackathon process to:

1. Refine the problem and user journey.
2. Complete wireframes and technical architecture.
3. Develop the initial prototype.
4. Build a usable Minimum Viable Product.
5. Test the concept with potential users.
6. Begin developing a community around the project.

---

# 🤝 Join GeoMzansi Impact Lab

The project is currently being started independently, but the ambition is not to build it from only one perspective.

**GeoMzansi Impact Lab** is interested in meeting hardworking, creative contributors who genuinely connect with the vision and want to help shape it.

Skills that could strengthen the project include:

* Mobile development
* Frontend development
* Backend engineering
* UI/UX design
* GIS and geospatial technology
* Data engineering
* Tourism research
* Business development
* Marketing
* Brand and visual design
* Product management
* Storytelling

We particularly encourage participation from **women, people of colour and other underrepresented voices in technology**, while building the team around creativity, contribution, collaboration and commitment to the project.

Different perspectives are not viewed as a complication.

They are part of how a better South African platform can be built.

---

# 👨‍🔬 Founder Capability

The project founder brings a multidisciplinary background spanning:

* Chemical engineering
* Analytical and process thinking
* Software and systems development
* SQL/database systems
* Point-of-sale system development
* E-commerce development
* Website development
* Systems integration
* Digital marketing
* Business process design
* Data-driven problem solving
* Hackathon experience

This combination of engineering, software and commercial thinking forms the initial foundation for developing Khaya Mzansi 360.

---

# 🛣️ Long-Term Vision

The long-term ambition is for Khaya Mzansi 360 to evolve from discovery into a broader South African travel ecosystem where users can eventually:

**Discover → Understand → Plan → Navigate → Reserve → Book → Experience**

from one platform.

That may eventually include:

* Activity bookings
* Attraction tickets
* Restaurant reservations
* Local-guide bookings
* Experience payments
* Accommodation integrations
* Travel routes
* Community tourism
* Business dashboards
* Traveller reviews
* Personalised journeys

The vision is intentionally larger than the hackathon.

The hackathon is the starting point.

---

# 🌱 Impact

Khaya Mzansi 360 aims to create value on both sides of the tourism economy.

### For travellers

Make South Africa easier and more enjoyable to discover.

### For businesses

Create greater visibility and routes to customers.

### For communities

Help tourism activity reach smaller and lesser-known destinations.

### For South Africa

Create a locally designed digital platform capable of showcasing the depth of the country to both South Africans and the world.

---

# 🏆 Geekulcha Annual Hackathon 2026

**Challenge Category:** Brand New
**Team:** GeoMzansi Impact Lab
**Project:** Khaya Mzansi 360

This repository will document the project's development during the Geekulcha hackathon, including architecture, research, wireframes, prototypes and source code.

Participation in the hackathon does not imply endorsement of this project by the event's sponsors or partners.

---

# 📂 Proposed Repository Structure

```text
khaya-mzansi-360/
│
├── README.md
├── LICENSE
├── docs/
│   ├── architecture/
│   ├── research/
│   ├── user-journey/
│   └── wireframes/
│
├── app/
│   ├── mobile/
│   └── web/
│
├── backend/
│   ├── api/
│   ├── database/
│   └── services/
│
├── data/
│   ├── sample/
│   └── schemas/
│
├── tests/
│
└── .github/
    └── workflows/
```

---

# 🔐 Data & Privacy

The project intends to follow responsible data-management principles and applicable South African privacy requirements as development progresses.

Location information and personalisation features should be implemented using privacy-conscious design and appropriate user consent.

---

# 📜 Licence

A project licence will be selected as the repository and collaboration model develops.

**Copyright © 2026 Khaya Mzansi 360 / GeoMzansi Impact Lab.**

---

## 🇿🇦 Our Vision

> **Build technology in South Africa that helps people experience South Africa.**

**Khaya Mzansi 360**
*Discover. Experience. Live South Africa.*
