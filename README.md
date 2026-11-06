# LuminPay developer docs

Source for [docs.luminpay.co](https://docs.luminpay.co), built with [Mintlify](https://mintlify.com).

| Path | What it is |
|---|---|
| `quickstart.mdx`, `environments.mdx`, `authentication.mdx` | Getting started |
| `guides/` | Payments, webhooks, networks, errors, Postman |
| `api-reference/` and `openapi.json` | API reference, generated from `openapi.json` |
| `luminpay.postman_collection.json` | Postman collection with the same endpoints |

## Preview locally

```bash
npm i -g mint
mint dev
```

Run `mint broken-links` before opening a pull request.

## Keep it in step with the API

When an endpoint, request field or webhook changes in `luminpay-backend`, update `openapi.json`, the Postman collection and the matching guide in the same change.
