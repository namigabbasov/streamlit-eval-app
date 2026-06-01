# EvalReader — Stanford Law Course Evaluation Extractor

Extracts and analyzes handwritten student comments from Stanford Law course evaluation PDFs using GPT-4.1 Vision.

## Local development

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Deploy to Streamlit Cloud

1. Push this repo to GitHub
2. Go to [share.streamlit.io](https://share.streamlit.io) → **New app**
3. Select your repo, set main file to `app.py`
4. Under **Advanced settings → Secrets** add:
```toml
OPENAI_API_KEY = "sk-proj-your-key-here"
```
5. Click **Deploy**

## Access control

To restrict access to specific users:
- Go to your app on Streamlit Cloud → **Settings → Sharing**
- Set to **Only specific people** and add `@law.stanford.edu` emails
