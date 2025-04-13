<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Response
```json
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
}
