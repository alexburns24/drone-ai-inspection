## drone-ai-inspection
GenAI and computer vision system for automated infrastructure inspection reporting

## Overview
This project demonstrates an end-to-end AI workflow for automated infrastructure inspection using computer vision concepts and GenAI-style reporting.

Users can upload an image and receive a structured AI-generated inspection report including:
- Issue detection
- Risk level
- Recommended actions
- Business impact

---

##  Key Features
- Interactive web app built with Streamlit
- Image upload and visualization
- Simulated AI-based issue detection
- Structured JSON outputs for downstream use
- Business-focused reporting (risk, impact, actions)

---

## Architecture

Image → Issue Detection → Report Generation → Structured Output

---

## How to Run
pip install -r requirements.txt
streamlit run app.py

## Example Output

```json
{
  "summary": "Detected vegetation encroachment with confidence 0.91",
  "risk_level": "High",
  "recommended_action": "Schedule inspection within 7 days",
  "business_impact": "Potential outage risk if vegetation contacts power lines"
}
```

## Business Impact
This project demonstrates how AI can:
- Improve infrastructure inspection efficiency
- Standardize reporting workflows
- Enable proactive maintenance decisions
- Translate technical outputs into business insights

## Futre Improvements
- Replace mock classifier with real CV model (CLIP, etc.)
- Add LLM-based report generation (OpenAI / local models)
- Integrate retrieval-augmented generation (RAG) with inspection guidelines
- Deploy as API for enterprise integration

## Author
Alex Burns
Senior Data Scientist
