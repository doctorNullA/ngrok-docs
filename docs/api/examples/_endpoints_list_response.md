<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2025-01-08T10:06:26Z",
			"hostport": "c922187ea75a.ngrok.paid:443",
			"id": "ep_2rLG917JwOEiqLFoyw7kNS4Wh1p",
			"name": "command_line",
			"principal": {
				"id": "usr_2rLG6WgX2p3Mk9nhsGx718xy2K4",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://c922187ea75a.ngrok.paid",
			"tunnel": {
				"id": "tn_2rLG917JwOEiqLFoyw7kNS4Wh1p",
				"uri": "https://api.ngrok.com/tunnels/tn_2rLG917JwOEiqLFoyw7kNS4Wh1p"
			},
			"tunnel_session": {
				"id": "ts_2rLG9510lSYFFWSRRSVPreWxyIx",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2rLG9510lSYFFWSRRSVPreWxyIx"
			},
			"type": "ephemeral",
			"updated_at": "2025-01-08T10:06:26Z",
			"upstream_url": "http://localhost:80",
			"url": "https://c922187ea75a.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-01-08T10:06:23Z",
			"domain": {
				"id": "rd_2rLG8hiwhFyIne0MmTXfybzZ1Cx",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2rLG8hiwhFyIne0MmTXfybzZ1Cx"
			},
			"edge": {
				"id": "edgtls_2rLG8fbtdR8vpZ5JKqS9DPKkq5H",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2rLG8fbtdR8vpZ5JKqS9DPKkq5H"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2rLG8dXURJFevM0zyD77e9cfLEh",
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2025-01-08T10:06:23Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
