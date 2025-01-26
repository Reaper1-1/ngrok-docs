<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"reserved_domains": [
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2sA6QSamIhpH4IzVcjZGyWDlE3t",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2sA6QSamIhpH4IzVcjZGyWDlE3t"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.3gvmlqfyadjg8xsze.local-ngrok-cname.com",
			"created_at": "2025-01-26T10:06:55Z",
			"domain": "myapp.mydomain.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2sA6QYvISFvslWgURdpn6ZKBe2M",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2sA6QYvISFvslWgURdpn6ZKBe2M"
		},
		{
			"acme_challenge_cname_target": null,
			"certificate": null,
			"certificate_management_policy": {
				"authority": "letsencrypt",
				"private_key_type": "ecdsa"
			},
			"certificate_management_status": {
				"provisioning_job": {
					"error_code": null,
					"msg": "Managed certificate provisioning in progress.",
					"retries_at": null,
					"started_at": "2025-01-26T10:06:56Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.3gvmlqfyadjg8xsze.local-ngrok-cname.com",
			"created_at": "2025-01-26T10:06:56Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2sA6QezgCZFWCTqv6xirDSeFHvD",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2sA6QezgCZFWCTqv6xirDSeFHvD"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
