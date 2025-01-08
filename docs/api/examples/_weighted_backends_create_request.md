<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Request

```bash
curl \
-X POST \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"backends":{"bkdhr_2rLG9Ul89ahS2pgdJSNF2VOOZpI":1,"bkdhr_2rLG9YXT7xHm2z8xvOuyUTKkyfP":0},"description":"acme weighted","metadata":"{\"environment\": \"staging\"}"}' \
https://api.ngrok.com/backends/weighted
```
