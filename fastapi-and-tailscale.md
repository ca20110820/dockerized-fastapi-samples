# FastAPI and Tailscale

FastAPI with Tailscale (`serve` or `funnel`).

FastAPI Development:
```bash
fastapi dev --host 127.0.0.1 --port 8000
```

Tailscale serve:
```bash
tailscale serve 8000
```

URL:
```
https://<machine-hostname>.<tailnet>.ts.net/
```

The API Service(s) will be accessible to devices connected to your tailnet.
