# 7NAGA — 7 Candle GOLD Intraday EA

**Symbol:** GOLD (XAUUSD)  
**Broker:** 5-digit pricing  
**Version:** MQL4 + MQL5

---

## Strategy

Ambil HIGH dan LOW dari 7 candle sebelumnya (M1). Setel Buy Stop di atas HIGH +100 poin dan Sell Stop di bawah LOW -25 poin, dengan pembulatan ke kelipatan 5.

**Setup:**
- Analisis: 09:30 WIB
- Expiry: 17:00 WIB
- Skip: Senin, NFP, FOMC, CPI, US Holiday

**Exit:**
- 6 zona TP (10/15/30/50/100/200 pips) — masing-masing 0.01 lot
- SL = harga pasangan (oneshot)
- Distance filter: 70-200 pips

---

*7 candles. 1 direction. Zero compromise.*