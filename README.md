
# 🚀 AI Startup Blueprint Generator

This Gradio app uses a language model (Granite-3-3-8B-Instruct) to generate detailed startup blueprints from user-provided inputs.

## 💡 Features
- User inputs: domain, audience, budget, country, timeline
- Output: Structured blueprint with MVP, Tech stack, Go-to-market, etc.
- Built with: Gradio + Transformers

###<img width="1760" height="969" alt="Screenshot 2025-08-05 131610" src="https://github.com/user-attachments/assets/45904b95-945a-4658-b3e8-85797d36ff9c" />
<img width="1739" height="328" alt="image" src="https://github.com/user-attachments/assets/504fe84a-4bbf-452c-9800-9119c746952c" />






#### 🧠 Model Details

- Model: `granite-3-3-8b-instruct`
- Platform: IBM Watsonx Studio (Cloud Lite)
- Generation Method: `foundation_models.Model.generate()`

## 💡 How It Works

1. Prompt is defined in the notebook.
2. Granite model generates a 6-section startup blueprint.
3. Gradio interface displays that response for demo.
4. Response and UI used for submission, presentation, and screenshots.

## 🛠️ Setup
```bash
pip install -r requirements.txt

