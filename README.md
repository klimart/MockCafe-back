# MockCafe-Backend
Magento backend for pwa storefront MockCafe theme

[Warden Documentation](https://docs.warden.dev/environments/magento2.html)

Backend login 2FA
```
> warden shell
> printf "2FA Authenticator Codes:\n%s\n" "$(oathtool -s 30 -w 10 --totp --base32 "${TFA_SECRET}")"
```

Local Site Urls
* https://dev.mock-cafe.test/
* https://dev.mock-cafe.test/backend/
* https://rabbitmq.mock-cafe.test/
* https://elasticsearch.mock-cafe.test/
