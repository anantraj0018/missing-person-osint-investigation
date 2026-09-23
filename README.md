# Missing Person — OSINT Investigation
> A practical Open Source Intelligence (OSINT) investigation based on the Missing Person room from TryHackMe.

## Overview

This project documents an OSINT investigation involving a person who went on holiday in 2025 and later became unreachable.
The investigation began with images provided by the TryHackMe challenge. Various OSINT techniques were used to identify locations, investigate events, analyze metadata, and correlate information from publicly available sources.

## Objectives

- Identify locations from images
- Analyze image metadata
- Perform reverse image searches
- Investigate geographical clues
- Research relevant events
- Investigate publicly available social-media information
- Correlate evidence from multiple sources
- Document the investigation process

## Tools and Techniques

| Tool / Technique | Purpose |
|---|---|
| Google Search | Information discovery |
| Reverse Image Search | Image identification |
| Google Maps / Google Earth | Location investigation |
| Online Metadata Analyzer | EXIF metadata analysis |
| Social Media | Public information research |
| OSINT Techniques | Evidence collection and correlation |

## Initial Evidence

The investigation started with two images:

- MotoGP.jpg — A motorcycle racing circuit image containing visible PERTAMINA branding.
- food.jpg — A photograph of a colorful Mexican-themed restaurant.

## Investigation Workflow

Initial Images
      |
      v
Image Analysis
      |
      v
Metadata Analysis
      |
      v
Circuit Identification
      |
      v
Event Investigation
      |
      v
Restaurant Identification
      |
      v
After-Party Investigation
      |
      v
DJ Identification
      |
      v
Location Investigation
      |
      v
Social Media Investigation
      |
      v
Evidence Correlation
      |
      v
Final Findings

## Investigation Summary

### Q1 — Racing Circuit

**Clue:** PERTAMINA branding was visible in MotoGP.jpg.

**Method:** Visual analysis and reverse image search.

**Finding:** Pertamina Mandalika International Street Circuit, Lombok, Indonesia.

### Q2 — Event Date

**Method:** Examined available image metadata and cross-checked the information with public MotoGP event information.

**Finding:** 03–05/10/2025.

### Q3 — Restaurant

**Clue:** The text "CANTINA MEXICANA" was visible in food.jpg.

**Method:** Reverse image search, image-based geolocation, and comparison of restaurant photographs.

**Finding:** Cantina Mexicana, Kuta, Lombok, Indonesia.

### Q4 — Photo Timestamp

**Method:** Used an online metadata analyzer to examine the EXIF information of food.jpg.

**Finding:** The Date/Time Original metadata field was used to determine the capture time.

**Answer:** [INSERT HH:MM:SS]

### Q5 — Bar Location

**Clue:** The missing person's message mentioned a MotoGP after-party.

**Method:** Investigated MotoGP after-party events and venue information.

**Finding:** Mandalika Beach Club.

### Q6 — Local DJ

**Method:** Investigated MotoGP after-parties and publicly available social-media event content.

**Finding:** BONG LELEH.

### Q7 — Cave

**Clue:** The missing person planned to visit a cave on 6 October 2025.

**Method:** Investigated caves around the Kuta/Mandalika area.

**Finding:** Gua Sumur.

### Q8 — Old Business

**Lead:** BONG LELEH.

**Method:** Investigated publicly available social-media information connected to the DJ and his previous business.

**Finding:** A phone number associated with the old business was identified.


## Key Learning
This investigation demonstrated that OSINT investigations often require multiple pivots.
When an initial search produced ambiguous or incorrect results, alternative clues were used to continue the investigation. This highlighted the importance of:
- Critical thinking
- Verification
- Cross-referencing
- Documentation
- Evidence correlation

  ## Detailed Report
The complete investigation report, including screenshots, methodology, evidence, and findings, is available in the `Report` folder.
[View the Investigation Report](Report/Missing-Person-OSINT-Investigation.pdf)


## Disclaimer
This project was conducted in an authorized TryHackMe training environment for educational purposes.
The techniques documented in this repository should only be used for legal, ethical, and authorized investigations.

## Author
**Anant Raj**
B.Tech Computer Science & Engineering  
GLA University, Mathura
**Focus:** Cybersecurity | OSINT | Digital Investigation
