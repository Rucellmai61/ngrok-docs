<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Response
```json
{
  "next_page_uri": null,
  "reserved_domains": [
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_2vfawUvrld6jY6IrQRktN8sW3UC",
        "uri": "https://api.ngrok.com/tls_certificates/cert_2vfawUvrld6jY6IrQRktN8sW3UC"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.5spie5hgq8pawaw7v.local-ngrok-cname.com",
      "created_at": "2025-04-13T10:07:00Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2vfawV9k9aJFYWGDdjQCHr3TwZ4",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2vfawV9k9aJFYWGDdjQCHr3TwZ4"
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
          "started_at": "2025-04-13T10:07:00Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.5spie5hgq8pawaw7v.local-ngrok-cname.com",
      "created_at": "2025-04-13T10:07:00Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2vfawS4A1hb64ltuCiPbrXTxsar",
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2vfawS4A1hb64ltuCiPbrXTxsar"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
