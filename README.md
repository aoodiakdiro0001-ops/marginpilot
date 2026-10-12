# 📈 MarginPilot — E-Commerce Profit Calculator (MIT)

Recommended price, breakeven units and exact net profit from real cost
inputs. UI in EN/TR/AR. Static single file + README.

## Model (shown openly in-app)

expected = (1−r)·(P/(1+v) − P·(g+m) − per-order fixed) − r·returnCost
Recommended P = B/(A−m). VAT price-inclusive. Impossible margins are
refused with the math shown. Includes price ladder, ROAS, history,
per-currency display (TRY/USD/EUR at real 2026 rates).

## Money & contact

- `CONFIG.aff` partner slots (Shopify/Woo/iyzico/PayTR/Stripe/Aras) + REF.
- `CONFIG.ads` merchant-ad slot.
- Donate: BTC + USDT-TRC20 + IBANs.
- 📧 baranavisat@gmail.com · 📞 +90 531 326 37 22 · WhatsApp

## Run

```bash
cd marginpilot
python3 -m http.server 8080
```

## License

MIT. Verify with your accountant.
