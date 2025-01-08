<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"event_subscriptions": [
		{
			"created_at": "2025-01-08T10:06:30Z",
			"description": "ip policy creations",
			"destinations": [
				{
					"id": "ed_2rLG9WYLPLnPQ7WpZF7g9nBxkEp",
					"uri": "https://api.ngrok.com/event_destinations/ed_2rLG9WYLPLnPQ7WpZF7g9nBxkEp"
				}
			],
			"id": "esb_2rLG9YOKv17KLiWuqCGy7Oems46",
			"metadata": "{\"environment\": \"staging\"}",
			"sources": [
				{
					"type": "ip_policy_created.v0",
					"uri": "https://api.ngrok.com/event_subscriptions/esb_2rLG9YOKv17KLiWuqCGy7Oems46/sources/ip_policy_created.v0"
				}
			],
			"uri": "https://api.ngrok.com/event_subscriptions/esb_2rLG9YOKv17KLiWuqCGy7Oems46"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/event_subscriptions"
}
```
