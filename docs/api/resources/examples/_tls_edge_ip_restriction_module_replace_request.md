<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"ip_policy_ids":["ipp_2vfazsYKk1gFMMfPlzRvFMkOTlc","ipp_2vfazqRtn0rBIEuybPz69BZXatA"]}' \
https://api.ngrok.com/edges/tls/edgtls_2vfazuVhXbvxubAmfGEeL0zzoAw/ip_restriction
