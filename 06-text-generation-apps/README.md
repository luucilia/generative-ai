# IT Assistant

CloudOps AI Assistant is a Python application that uses Azure OpenAI (GPT-5 Mini) to analyze cloud infrastructure incidents and generate a concise operational runbook.

## Features

- Incident root cause analysis
- Possible causes identification
- Recommended actions
- Operational runbook generation
- Azure OpenAI integration

## Technologies

- Python 3.12
- Azure OpenAI
- OpenAI Python SDK
- python-dotenv

## Setup

1. Clone the repository.

2. Install dependencies.

```bash
pip install -r requirements.txt
```

3. Create a `.env` file.

```env
AZURE_OPENAI_ENDPOINT=https://<your-resource>.services.ai.azure.com/openai/v1
AZURE_OPENAI_API_KEY=your-api-key
AZURE_OPENAI_DEPLOYMENT=gpt-5-mini
```

4. Run the application.

```bash
python app.py
```

## Example

**Input**

```
After a software update, a company's website started returning an HTTP 404 error. Explain the error and the basic steps to troubleshoot and resolve it.
```

**Output**

- Root Cause
- Possible Causes
- Recommended Actions
- Operational Runbook