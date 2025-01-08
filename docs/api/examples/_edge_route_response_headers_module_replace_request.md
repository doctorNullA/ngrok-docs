<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Request

```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"add":{"Content-Security-Policy":"script-src 'self'","X-Frame-Options":"DENY"},"enabled":true}' \
https://api.ngrok.com/edges/https/edghts_2rLG9sqHOMuzVZUQ9kwrBsz3C2J/routes/edghtsrt_2rLG9wEu1NQCgexmFj70Pt5YBRR/response_headers
```
