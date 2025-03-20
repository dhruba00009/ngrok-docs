<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2025-03-20T10:07:08Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2uZnzn2XmG6atnBSqjadXHeNzg1",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2uZnzn2XmG6atnBSqjadXHeNzg1"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2uZnyY7OdiMSbUsHeo6MevCTtL8",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2uZnyY7OdiMSbUsHeo6MevCTtL8"
				},
				"enabled": true
			},
			"created_at": "2025-03-20T10:06:58Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2uZnyahU8WgbiA7DdEuuNxELsnK",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2uZnyahU8WgbiA7DdEuuNxELsnK"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
