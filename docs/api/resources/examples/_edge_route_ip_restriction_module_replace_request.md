<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"ip_policy_ids":["ipp_2vfazXxkFJmg3aV48ARDeSCaJWG","ipp_2vfazTXqWVNDoryRo6h8aIps9wj"]}' \
https://api.ngrok.com/edges/https/edghts_2vfazYPWSd4EvWPvEEc2Zxpe1VA/routes/edghtsrt_2vfazSasKMN3lQ8q8VSZgrTODqw/ip_restriction
