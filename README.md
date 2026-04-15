# Insurance Microsite Workflow MVP

Simple interactive prototype for the 3-step insurance workflow:

1. Upload CSV
2. Select use case
3. Submit job

## Run locally

Open `index.html` directly, or run a static server:

```bash
cd "tries/Insurance SSS/insurance-microsite-mvp-dashboard"
python3 -m http.server 4173
```

Then visit: `http://localhost:4173`

## What this prototype includes

- Drag-and-drop CSV upload
- Use case selection (Flood Risk Change / Underinsurance)
- CSV validation for required columns
- Real webhook submission with processing indicator (queued -> processing -> completed)
- Results preview table
- Download output CSV from webhook response (or generated from webhook JSON rows)
- Simulated "Send to CRM"
- Downloadable CSV templates by use case

## Important

This is a front-end MVP prototype that submits directly to an n8n webhook.
