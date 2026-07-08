# Multi-Agent Travel Planner System (CrewAI)

An autonomous multi-agent intelligence system built using **CrewAI** and **Groq (LLaMA 3.3)** that collaborates sequentially to generate highly customized travel itineraries and budget profiles.

## Repository Contents
1. **`travelplanner-falakbaweja.ipynb`**: The complete, runnable notebook code implemented in Kaggle.
2. **`Multi_Agent_Travel_Planner_Report.pdf`**: A comprehensive technical report detailing the multi-agent architecture, prompt strategies, and system evaluation.
3. **`requirements.txt`**: Python dependencies required to run this system locally.

## 🤖 System Architecture & Agents
The system orchestrates 7 distinct agents to handle specialized domains:
1. **Travel Preference Analyst** - Builds the core traveler profile.
2. **Destination Research Specialist** - Sources localized highlights and hidden gems.
3. **Transportation Planning Specialist** - Maps out optimal transit logistics.
4. **Accommodation & Budget Specialist** - Secures cost allocation safety boundaries.
5. **Itinerary Generation Specialist** - Chronologically sequences day-by-day schedules.
6. **Safety & Risk Specialist** - Evaluates real-time weather and travel warnings.
7. **Travel Report Specialist** - Compiles all intelligence into a unified dossier.
