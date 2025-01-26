<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"event_subscriptions": [
		{
			"created_at": "2025-01-26T10:07:18Z",
			"description": "ip policy creations",
			"destinations": [
				{
					"id": "ed_2sA6TMj24VtJdWH3bgJgdJuMqGP",
					"uri": "https://api.ngrok.com/event_destinations/ed_2sA6TMj24VtJdWH3bgJgdJuMqGP"
				}
			],
			"id": "esb_2sA6TM76YuEpQUKyy9L2KteeNWs",
			"metadata": "{\"environment\": \"staging\"}",
			"sources": [
				{
					"type": "ip_policy_created.v0",
					"uri": "https://api.ngrok.com/event_subscriptions/esb_2sA6TM76YuEpQUKyy9L2KteeNWs/sources/ip_policy_created.v0"
				}
			],
			"uri": "https://api.ngrok.com/event_subscriptions/esb_2sA6TM76YuEpQUKyy9L2KteeNWs"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/event_subscriptions"
}
```
