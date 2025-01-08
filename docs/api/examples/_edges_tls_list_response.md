<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2025-01-08T10:06:34Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2rLGA0W86B14FZOzX0aFaC0Xux2",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2rLGA0W86B14FZOzX0aFaC0Xux2"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2rLG8c5a1uiVLcOnYWdGLszlyQC",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2rLG8c5a1uiVLcOnYWdGLszlyQC"
				},
				"enabled": true
			},
			"created_at": "2025-01-08T10:06:23Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2rLG8fbtdR8vpZ5JKqS9DPKkq5H",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2rLG8fbtdR8vpZ5JKqS9DPKkq5H"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
