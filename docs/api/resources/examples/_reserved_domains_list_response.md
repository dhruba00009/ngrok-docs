<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"reserved_domains": [
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2uZnwaB1QivWjWroXL9tspQqfcH",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2uZnwaB1QivWjWroXL9tspQqfcH"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.35jdibp9t5p2a7h8g.local-ngrok-cname.com",
			"created_at": "2025-03-20T10:06:42Z",
			"domain": "myapp.mydomain.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2uZnwYgLe7IMCfIdD263OXpoWUk",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2uZnwYgLe7IMCfIdD263OXpoWUk"
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
					"started_at": "2025-03-20T10:06:42Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.35jdibp9t5p2a7h8g.local-ngrok-cname.com",
			"created_at": "2025-03-20T10:06:42Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2uZnwXGmz9INkXuuLw1IA4CCsh8",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2uZnwXGmz9INkXuuLw1IA4CCsh8"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
