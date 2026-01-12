# Plot — Product Design Document

## Overview
Plot is a location- and plan-first dating application designed to shift online dating away from passive swiping and toward intentional, real-world connection. Instead of matching based primarily on profiles, users match around a concrete first-date plan defined by a specific activity, time, and place. Identity and compatibility are contextual and secondary to shared intention.

Plot’s core success metric is not time spent in-app, but successful in-person meetings.

---

## Design Principles

1. **Plans Before Profiles**  
   The date plan is always the primary object. Profiles exist to validate comfort and compatibility, not to drive initial attraction.

2. **Intentionality Over Abundance**  
   Reduce cognitive overload and decision fatigue by limiting interactions to real, time-bound plans.

3. **Action-Oriented UX**  
   Every surface of the app should encourage users to leave the app and execute a plan.

4. **Low Friction, Low Pressure**  
   Remove the social burden of inventing a first date or sustaining prolonged pre-date messaging.

5. **City-as-Interface**  
   The app should feel closer to a city guide or events map than a traditional dating gallery.

---

## Target Users

- Young/middle-aged adults seeking intentional dating
- Individuals open to both serious relationships and casual but meaningful experiences
- Users who value experiences, exploration, and structure

---

## Core Objects

### 1. User Profile
Tagged to every date pin and easily accessible

**Key Elements:**
- Profile photo(s)
- First name, age
- Short bio or intent statement
- Interests/hobbies (used contextually)
- Past dates completed (optional, privacy-controlled)
- Active pins and pending requests

Profiles are intentionally minimal and never browsed independently of a plan.

---

### 2. Date Pin (Primary Object)
A Pin represents a proposed first date.

**Required Attributes:**
- Activity title (e.g., “Sunrise Hike & Coffee”)
- Location (map-based, GPS-anchored) (can be a general area)
- Duration estimate
- Brief description or vibe tags

**Optional Attributes:**
- Cost indicator ($–$$$)
- A suggested date/day of the week
- Time of day
- Weather sensitivity

Each pin is visually represented on the live map and includes the creator’s profile preview.

---

## Primary User Workflows

### Workflow A: Creating a Date Pin

1. User taps “Create Pin”
2. Inputs location
3. Defines activity a required attributes
4. Adds optional attributes
5. Publishes pin to the live map
6. Pin becomes discoverable until accepted or expired

**Design Intent:** Empower users to lead with intention and remove anxiety around planning.

---

### Workflow B: Exploring and Requesting a Match

1. User opens the map view
2. Browses nearby pins visually
   - Alternatively searches by activity keyword
3. Taps a pin or search result to view details and creator profile
4. Requests to join the plan
5. Waits for acceptance

**Design Intent:** Discovery is spatial, temporal, and experiential rather than appearance-driven.

---

### Workflow C: Match Acceptance & Messaging

1. Pin creator reviews incoming requests
2. Views requester’s profile
3. Accepts one request (pin closes)
4. Match is created
5. In-app messaging opens

---

## Map & Navigation Structure

### Primary Navigation Tabs

- **Map (Home):** Live pins nearby (contains search bar and filters that apply to the search and the map)
- **Create:** New date pin
- **Messages:** Active matches only
- **Profile:** User settings and history

### Map UI Behavior

- Pins clustered by density
- Visual differentiation by activity type
- Filters for distance, time window, activity

---

## User Experience Considerations

- Limited number of active pins per user
- In-app reporting and blocking
- Emphasis on excitement and anticipation
- Copy reinforces action and momentum
- Minimal validation metrics (no likes, no swipe counts)

---

## Success Metrics

- Percentage of pins resulting in matches
- Percentage of matches resulting in completed dates
- Repeat pin creation

---

## Brand & Tone

### Voice
- Confident
- Intentional
- Experience-driven
- Optimistic but grounded

### Taglines
- “Stop swiping on people. Start matching on plans.”
- “Where and when comes before who.”
- “Don’t just find a match. Find an exciting reason to get out of the house.”

## Summary

Plot is designed as an antidote to passive, performative dating. By centering the product around concrete plans, the app aligns incentives with real connection, decisiveness, and presence in the physical world. The design prioritizes clarity, momentum, and shared intention—turning dating back into something people actually do, not just browse.

