<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Response
```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-04-13T10:07:21Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_2vfayKJanheJnpwYBSbrtFgoz4w",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2vfayKJanheJnpwYBSbrtFgoz4w"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2vfazAQWcfEgh4QlcyqaSNFsJKt",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-04-13T10:07:21Z",
      "uri": "https://api.ngrok.com/endpoints/ep_2vfazAQWcfEgh4QlcyqaSNFsJKt",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-04-13T10:07:19Z",
      "hostport": "9ff7c06237ab.ngrok.paid:443",
      "id": "ep_2vfayptBtsMf0fHnD6mGXC8KMri",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_2vfawQVWBKF53uHMAGQGEVDVVBS",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://9ff7c06237ab.ngrok.paid",
      "tunnel": {
        "id": "tn_2vfayptBtsMf0fHnD6mGXC8KMri",
        "uri": "https://api.ngrok.com/tunnels/tn_2vfayptBtsMf0fHnD6mGXC8KMri"
      },
      "tunnel_session": {
        "id": "ts_2vfayt9crACNgb268nT5QcYRFZR",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_2vfayt9crACNgb268nT5QcYRFZR"
      },
      "type": "ephemeral",
      "updated_at": "2025-04-13T10:07:19Z",
      "upstream_url": "http://localhost:80",
      "url": "https://9ff7c06237ab.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-04-13T10:07:17Z",
      "domain": {
        "id": "rd_2vfayKJanheJnpwYBSbrtFgoz4w",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2vfayKJanheJnpwYBSbrtFgoz4w"
      },
      "edge": {
        "id": "edgtls_2vfayZ4IzcJv2it6KM1zjkXtpal",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_2vfayZ4IzcJv2it6KM1zjkXtpal"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2vfayYpqUYGxFb52FNTzTwrj4co",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-04-13T10:07:17Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
