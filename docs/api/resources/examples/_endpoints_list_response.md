<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2025-01-26T10:07:16Z",
			"description": "sample cloud endpoint",
			"domain": {
				"id": "rd_2sA6SWO74Wos5ie8yzbDHYZWOyQ",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2sA6SWO74Wos5ie8yzbDHYZWOyQ"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2sA6T6AtBPLdl1ygBIEuKZ7319Q",
			"metadata": "{\"environment\": \"staging\"}",
			"pooling_enabled": false,
			"proto": "https",
			"public_url": "https://endpoint-example2.com",
			"traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
			"type": "cloud",
			"updated_at": "2025-01-26T10:07:16Z",
			"uri": "https://api.ngrok.com/endpoints/ep_2sA6T6AtBPLdl1ygBIEuKZ7319Q",
			"url": "https://endpoint-example2.com"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-01-26T10:07:15Z",
			"hostport": "23ca5f08591f.ngrok.paid:443",
			"id": "ep_2sA6SzNazr66tCTZ7TGjUY0XPPi",
			"name": "command_line",
			"pooling_enabled": false,
			"principal": {
				"id": "usr_2sA6QSnMH3ompGP7bHd9HlsmmAV",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://23ca5f08591f.ngrok.paid",
			"tunnel": {
				"id": "tn_2sA6SzNazr66tCTZ7TGjUY0XPPi",
				"uri": "https://api.ngrok.com/tunnels/tn_2sA6SzNazr66tCTZ7TGjUY0XPPi"
			},
			"tunnel_session": {
				"id": "ts_2sA6SxmW0cdTQQDIOkpjIunz8d9",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2sA6SxmW0cdTQQDIOkpjIunz8d9"
			},
			"type": "ephemeral",
			"updated_at": "2025-01-26T10:07:15Z",
			"upstream_url": "http://localhost:80",
			"url": "https://23ca5f08591f.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-01-26T10:07:12Z",
			"domain": {
				"id": "rd_2sA6SWO74Wos5ie8yzbDHYZWOyQ",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2sA6SWO74Wos5ie8yzbDHYZWOyQ"
			},
			"edge": {
				"id": "edgtls_2sA6SShD5rO3sxUoTnNEqq1NKMA",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2sA6SShD5rO3sxUoTnNEqq1NKMA"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2sA6SRPQunB3TrAVHJjohE5tNUp",
			"pooling_enabled": false,
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2025-01-26T10:07:12Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
