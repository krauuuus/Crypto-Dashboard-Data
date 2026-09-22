# crypto-research-data

Processed outputs from the [Crypto Research Dashboard](https://github.com/krauuuus/Crypto-Dashboard) pipelines.

Raw data (exchange trade files, ~GB) is never stored here — only aggregated results.

## Structure

```
bucket_analysis/      Monthly transaction size bucket stats (5 exchanges x 4 assets)
crypto_prices/        Daily OHLCV for 7-crypto basket (CryptoCompare)
crypto_stability/     DFM factor, eGARCH shock, rolling QR betas, FI/FF classification
imf_cper/             IMF crypto-based parallel exchange rates (WP-CPER dataset)
```

## Update frequency

Pipelines in the dashboard repo write here automatically.
Each push corresponds to one data refresh cycle.

## Citation

If using the IMF CPER data:
> Graf von Luckner, C., Koepke, R., & Sgherri, S. (2024).
> "Crypto as a Marketplace for Capital Flight." IMF Working Paper No. 2024/133.
