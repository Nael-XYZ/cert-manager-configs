# Cert Manager Configs 🔐

cert-manager configurations for automated TLS certificate management.

## Issuers

| Issuer | Use Case | Rate Limit |
|--------|----------|-----------|
| Let's Encrypt Prod | Production | 50 certs/week |
| Let's Encrypt Staging | Testing | Unlimited |
| Cloudflare DNS01 | Wildcard certs | N/A |

## Quick Start

```bash
kubectl apply -f issuers/
kubectl apply -f certificates/
```

## License

MIT