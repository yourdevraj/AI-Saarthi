# AI SAARTHI – Rajasthan
## A Unified Skill, Career & Opportunity Navigator for Rural Youth

AI Saarthi is a simple, mobile-friendly and AI-supported guidance platform designed to help rural youth and college students gain clarity about their skills, career pathways, government schemes, scholarships, and district-level opportunities.

The solution is built for low-data environments, follows visual-first design principles, and requires no formal training, enabling easy adoption across schools, colleges, ITIs, and youth centers.

---

## 1. Problem Statement

Millions of rural youth and first-generation learners transition from education to employment without understanding their strengths or future direction.

### Key Challenges
- Lack of structured career guidance in rural areas  
- Students and college learners relying on guesswork  
- No single platform for schemes, scholarships, and opportunities  
- Limited awareness of district-level jobs and training  
- Additional mobility and exposure barriers for girls and marginalized youth  
- Existing platforms being text-heavy, fragmented, or urban-focused  

This leads to confusion, wrong career choices, underemployment, and loss of confidence.

**India does not lack talent. It lacks clarity.**

---

## 2. Solution Overview

AI SAARTHI provides that clarity through a five-layer unified guidance system designed for rural youth and college learners.

### 1. Skill and Interest Mapping
- Short, visual assessment  
- Simple icons and local-language prompts  
- Identifies strengths and interests  

### 2. AI Career Match Engine
- Maps user profiles to suitable career clusters  
- Suggests relevant skills and pathways  

### 3. Unified Opportunity Hub

**Government Schemes**
- PMKVY  
- National Career Service (NCS)  
- Apprenticeship Programs  
- NSDC Courses  
- MSME Support Initiatives  

**Scholarship Finder**
- Based on education level, gender, income, category, merit, and state eligibility  

**District Opportunity Map**
- ITIs  
- Apprenticeships  
- MSMEs  
- Local job clusters  
- Training centers  
- Government initiatives  

### 4. Personalized Roadmap
- Clear and actionable plans for short-term, mid-term, and long-term goals  

### 5. Live Guidance from Experts
- Optional mentorship with Skill India trainers, counsellors, educators, and industry volunteers  

---

## 3. Key Features

- Visual, low-text, and local-language interface  
- Works in low-data or limited internet environments  
- Unified access to schemes, scholarships, and jobs  
- Designed for rural and semi-urban realities  
- Suitable for students, college learners, and job seekers  
- Scalable across colleges, ITIs, NSS units, and youth programs  
- No formal training required for adoption  

---

## 4. User Journey

1. User opens the platform  
2. Completes skill and interest mapping  
3. Receives matched career clusters  
4. Explores schemes, scholarships, and district opportunities  
5. Follows a personalized roadmap  
6. Optionally connects with an expert mentor  

---

## 5. Architecture Flow

User Input  
↓  
Skill and Interest Mapping  
↓  
AI Career Match Engine  
↓  
Unified Opportunity Hub  
- Government Schemes  
- Scholarships  
- District Opportunities  
↓  
Personalized Roadmap  
↓  
Live Mentor Support  

(Architecture diagram included in the repository.)

<img width="1080" height="1350" alt="4" src="https://github.com/user-attachments/assets/44fc37df-b31d-4dbb-81c1-b68536145fb5" />

---

## 6. Prototype Screens

Available in the `/prototype` folder:
## homepage
<img width="1080" height="1350" alt="1" src="https://github.com/user-attachments/assets/ed0991db-9a8b-494d-980a-579deba6d7fd" />

## skill_test_screen
<img width="1080" height="1350" alt="2" src="https://github.com/user-attachments/assets/8761a1a2-a0ab-42f4-8726-e6eb28082407" />

## results_screen
<img width="1080" height="1350" alt="3" src="https://github.com/user-attachments/assets/3dc6f551-85a1-41e2-9c3d-5f5526947165" />

## architecture_diagram
<img width="1080" height="1350" alt="4" src="https://github.com/user-attachments/assets/47b776a4-c658-4393-bb4b-25871e3d25b2" />

These screens show the basic design and workflow of the platform.

---

## 7. Tech Stack

- Frontend: Mobile-responsive interface  
- Backend: Lightweight API-based structure  
- AI Layer: Rule-based scoring and interest mapping  

### Data Sources
- National Career Service  
- PMKVY Skill Directory  
- State Apprenticeship Portals  
- District Job Boards  
- Scholarship Databases  

The AI layer is intentionally lightweight to ensure scalability in rural environments.

---

## 8. Sample Input (JSON)

```json
{
  "user_id": "RU001",
  "interest_scores": {
    "technical": 72,
    "creative": 58,
    "service": 80
  },
  "location": "Churu, Rajasthan"
}
```
## 9. Sample Output (JSON)
```
{
  "career_clusters": [
    "IT Technician",
    "Customer Support Associate"
  ],
  "recommended_schemes": [
    "PMKVY Technical Courses",
    "NCS Apprenticeship"
  ],
  "scholarships": [
    "Post-Matric Scholarship"
  ],
  "district_opportunities": [
    "Apprenticeship - Local MSME Unit"
  ],
  "roadmap": {
    "short_term": "Skill foundation training",
    "mid_term": "Advanced skill certification",
    "long_term": "Apprenticeship or employment"
  }
}
````

## 10. Pseudo Code

```
def skill_mapping(responses):
    strengths = evaluate_interests(responses)
    careers = match_career_clusters(strengths)
    opportunities = fetch_opportunities(location, careers)
    roadmap = generate_roadmap(careers)
    return {
        "strengths": strengths,
        "careers": careers,
        "opportunities": opportunities,
        "roadmap": roadmap
    }
```

## 11. Impact Potential
    
Guidance for over one lakh rural youth and college learners
Increased awareness of government schemes and scholarships
Better alignment between skills and district opportunities
Improved employability and confidence among rural youth
Strong contribution to NEP 2020, Skill India, and Viksit Bharat 2047
AI Saarthi empowers youth with clarity, confidence, and access.

## 12. License

MIT License

Open for educational and non-commercial use under the Hack for Social Cause 2026 initiative.

## 13. Maintainer
Dev Raj Saini
Team Name: AI Saarthi – Rajasthan
State: Rajasthan

