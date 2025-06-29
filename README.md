# Blood Test Report Analyser

A FastAPI service that processes uploaded blood test PDF reports and provides evidence‑based medical, nutritional, and exercise recommendations using CrewAI agents.

---

## 🚀 Features

- **Automated Report Parsing**  
  Reads and cleans PDF blood test reports via `PyPDFLoader`.

- **Multi‑Agent Analysis**  
  - **Doctor**: Interprets lab results and gives medical insights.  
  - **Verifier**: Validates report structure and extracts key parameters.  
  - **Nutritionist**: Recommends dietary adjustments based on markers.  
  - **Exercise Specialist**: Designs safe exercise plans aligned with health data.

- **Search Integration**  
  Incorporates web searches (via `SerperDevTool`) to fetch guidelines or references.
