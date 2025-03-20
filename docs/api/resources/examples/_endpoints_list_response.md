<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2025-03-20T10:07:03Z",
			"description": "sample cloud endpoint",
			"domain": {
				"id": "rd_2uZnySYytMU9YlC60b0FwiiZyuM",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2uZnySYytMU9YlC60b0FwiiZyuM"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2uZnzDyOxu5WAF1jNkRIsAisK5Q",
			"metadata": "{\"environment\": \"staging\"}",
			"pooling_enabled": false,
			"proto": "https",
			"public_url": "https://endpoint-example2.com",
			"traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
			"type": "cloud",
			"updated_at": "2025-03-20T10:07:03Z",
			"uri": "https://api.ngrok.com/endpoints/ep_2uZnzDyOxu5WAF1jNkRIsAisK5Q",
			"url": "https://endpoint-example2.com"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-03-20T10:07:00Z",
			"hostport": "1e23e7346d78.ngrok.paid:443",
			"id": "ep_2uZnyoLuvt4Fwzc6ggIXcTD3PoP",
			"name": "command_line",
			"pooling_enabled": false,
			"principal": {
				"id": "usr_2uZnwSPww9ckuS0D7bO5NENKX1q",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://1e23e7346d78.ngrok.paid",
			"tunnel": {
				"id": "tn_2uZnyoLuvt4Fwzc6ggIXcTD3PoP",
				"uri": "https://api.ngrok.com/tunnels/tn_2uZnyoLuvt4Fwzc6ggIXcTD3PoP"
			},
			"tunnel_session": {
				"id": "ts_2uZnylCoXLFVSDOzni90YeMuyfe",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2uZnylCoXLFVSDOzni90YeMuyfe"
			},
			"type": "ephemeral",
			"updated_at": "2025-03-20T10:07:00Z",
			"upstream_url": "http://localhost:80",
			"url": "https://1e23e7346d78.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-03-20T10:06:58Z",
			"domain": {
				"id": "rd_2uZnySYytMU9YlC60b0FwiiZyuM",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2uZnySYytMU9YlC60b0FwiiZyuM"
			},
			"edge": {
				"id": "edgtls_2uZnyahU8WgbiA7DdEuuNxELsnK",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2uZnyahU8WgbiA7DdEuuNxELsnK"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2uZnyYPQDEgLYYVCy8vQpcp3jYx",
			"pooling_enabled": false,
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2025-03-20T10:06:58Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
