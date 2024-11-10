# Last Update
**Date: 8 oct**

# 📝 API Documentation

# 🪪 Account Information
**Endpoint:** `/player_info`  
**Method:** `GET`  
**Description**
This endpoint retrieves account information based on the specified region and user ID.

### ☑️ Query Parameters

| Parameter | Type   | Required | Description                   |
|-----------|--------|----------|-------------------------------|
| `region`  | string | Yes      | The region code (`IND`, `BR`, `SG`, `RU`, `ID`, `TW`, `US`, `VN`, `TH`, `ME`, `PK`, `CIS`, `BD`).|
| `uid`     | string | Yes      | The user ID.                  |
### 📨 Request Example
```http
GET https://garena420ffapi.vercel.app/profile_info?uid={}&region={}&key={}
```
