# CryptoGate SDK (csharp-sdk)

Official SDK for the [CryptoGate](https://cryptogate.live) crypto-payments API —
accept Bitcoin, Ethereum, Litecoin, Dogecoin, Dash and ERC-20 tokens straight to your
own wallet.

```
dotnet add package CryptoGate
```

- **API reference:** https://docs.cryptogate.live/reference
- **OpenAPI spec:** https://docs.cryptogate.live/openapi.yaml
- **Generated from** `openapi.yaml` with [OpenAPI Generator](https://openapi-generator.tech)
  (`csharp`) — see `.github/workflows/generate.yml`. Do not hand-edit generated files.

## Quick start

Authenticate with a secret key (`Authorization: Bearer sk_live_…`, or `sk_test_…` for
sandbox), then create a payment. Send an `X-Idempotency-Key` on every create so a retried
request can't double-charge. Full, language-specific examples are generated below by CI.

## License

Apache-2.0 — see [LICENSE](LICENSE).
