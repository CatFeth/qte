# Quanteq
### Quick Install / Run (Interactive):
```
bash <(curl -fsSL https://qte.catfeth.link)
```

### Automated Install (Pass Panel IP directly):
```
bash <(curl -fsSL https://qte.catfeth.link) -p {PANEL_IP}
```
### Fast Re-apply on Production VPS (Skip APT Upgrade & Logs):
```
bash <(curl -fsSL https://qte.catfeth.link) -p {PANEL_IP} --skip-upgrade --no-logs
```

### Install without Cloudflare WARP:
```
bash <(curl -fsSL https://qte.catfeth.link) -p {PANEL_IP} --skip-warp
```
