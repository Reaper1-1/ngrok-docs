<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2025-01-26T10:07:23Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2sA6Tx0JCTZmR01Jp6up7MvBoxP",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2sA6Tx0JCTZmR01Jp6up7MvBoxP"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2sA6SWQk9Sep4rEFL3zYZeqAILE",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2sA6SWQk9Sep4rEFL3zYZeqAILE"
				},
				"enabled": true
			},
			"created_at": "2025-01-26T10:07:11Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2sA6SShD5rO3sxUoTnNEqq1NKMA",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2sA6SShD5rO3sxUoTnNEqq1NKMA"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
