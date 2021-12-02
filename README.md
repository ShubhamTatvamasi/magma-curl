# magma-curl

Get list of Tenants:
```bash
curl -X GET -ks \
  --cert admin_operator.pem \
  --key admin_operator.key.pem \
  https://api.magmaindia.org/magma/v1/tenants | jq
```

Get list of networks:
```bash
curl -X GET -ks \
  --cert admin_operator.pem \
  --key admin_operator.key.pem \
  https://api.magmaindia.org/magma/v1/networks | jq
```
