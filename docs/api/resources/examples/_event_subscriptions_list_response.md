<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"event_subscriptions": [
		{
			"created_at": "2025-03-20T10:07:04Z",
			"description": "ip policy creations",
			"destinations": [
				{
					"id": "ed_2uZnzEdh9lVrLOzZY2Fw6ynEHkc",
					"uri": "https://api.ngrok.com/event_destinations/ed_2uZnzEdh9lVrLOzZY2Fw6ynEHkc"
				}
			],
			"id": "esb_2uZnzHeicxbeSEb1C4Zq3mltKEN",
			"metadata": "{\"environment\": \"staging\"}",
			"sources": [
				{
					"type": "ip_policy_created.v0",
					"uri": "https://api.ngrok.com/event_subscriptions/esb_2uZnzHeicxbeSEb1C4Zq3mltKEN/sources/ip_policy_created.v0"
				}
			],
			"uri": "https://api.ngrok.com/event_subscriptions/esb_2uZnzHeicxbeSEb1C4Zq3mltKEN"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/event_subscriptions"
}
```
