<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"reserved_domains": [
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2rLG6fxqXU9EniTSPsqoNxrq8i9",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2rLG6fxqXU9EniTSPsqoNxrq8i9"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.3lpu42tnwb9vsxtwj.local-ngrok-cname.com",
			"created_at": "2025-01-08T10:06:07Z",
			"domain": "myapp.mydomain.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2rLG6iF5jz7U4uSHyW26TERZyUi",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2rLG6iF5jz7U4uSHyW26TERZyUi"
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
					"started_at": "2025-01-08T10:06:07Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.3lpu42tnwb9vsxtwj.local-ngrok-cname.com",
			"created_at": "2025-01-08T10:06:07Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2rLG6estoAZgTEvxBOtU9ogW7jK",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2rLG6estoAZgTEvxBOtU9ogW7jK"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
