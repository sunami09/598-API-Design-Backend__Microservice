# 598-API-Design-Backend__Microservice


## 📘 API Documentation

---

### `GET /AAPL`  
**Description**: Get real-time price info for a stock.

> **URL**: `http://<YOUR_VM_IP>:8089/AAPL`

**Response:**
```json
{
  "symbol": "AAPL",
  "price": 217.90,
  "change": -5.95,
  "exchange": "NASDAQ",
  ...
}
```

---

### `GET /AAPL`  
**Description**: Get grades consensus info for a stock.

> **URL**: `http://<YOUR_VM_IP>:8083/AAPL`

**Response:**
```json
[
  {
    "symbol": "AAPL",
    "buy": 28,
    "hold": 10,
    "sell": 5,
    "consensus": "Buy"
  }
]
```
