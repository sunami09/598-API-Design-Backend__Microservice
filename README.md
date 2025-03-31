# Tradient Architecture

## 📘 API Documentation
---
[High Level Design Doc - Excalidraw 🔗](https://excalidraw.com/#json=h1u4n5PznFNfu2EGknhMj,XOcVNeLJB42OPWeUjDLZRA)
---

<div align="center">
  <img src = "https://github.com/user-attachments/assets/75652c4a-fde5-4d2d-a77c-4366a633c7e7" />
</div>
---
---
<div align="center">
  <img src = "https://github.com/user-attachments/assets/c071fb00-6675-4660-b26b-eb9695221955" />
</div>
---

# Detailed doc, READ [here.](https://excalidraw.com/#json=h1u4n5PznFNfu2EGknhMj,XOcVNeLJB42OPWeUjDLZRA)

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


