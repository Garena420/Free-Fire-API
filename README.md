# Last Update
**Date: 10 nov**

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


### 💬 Response Example
```json
{
  "AccountInfo": {
    "accountId": "7802788212",
    "accountType": 1,
    "nickname": "ㅤㅤᎫᎧᗫㅤㅤ?",
    "region": "IND",
    "level": 57,
    "exp": 674160,
    "bannerId": 902000052,
    "headPic": 901041005,
    "rank": 213,
    "rankingPoints": 2352,
    "badgeCnt": 24,
    "badgeId": 1001000078,
    "seasonId": 42,
    "liked": 13259,
    "showRank": true,
    "lastLoginAt": "1731227598",
    "csRank": 221,
    "csRankingPoints": 130,
    "weaponSkinShows": [907193503],
    "maxRank": 213,
    "csMaxRank": 221,
    "accountPrefers": {},
    "createAt": "1685272409",
    "title": 904590054,
    "externalIconInfo": {
      "status": "ExternalIconStatus_NOT_IN_USE",
      "showType": "ExternalIconShowType_FRIEND"
    },
    "releaseVersion": "OB46",
    "showBrRank": true,
    "showCsRank": true,
    "socialHighLightsWithBasicInfo": {}
  },
  "profileInfo": {
    "equippedOutfit": [205000225, 211000435, 211000927, 203043019, 204000343, 214000023],
    "equippedSkills": [16, 706, 8, 1, 16, 1306, 8, 2, 16, 3406, 8, 3, 16, 6906]
  },
  "guildInfo": {
    "guildId": "67744100",
    "guildName": "PGㅤEMP1RE",
    "guildOwner": 972431060,
    "guildLevel": 6,
    "guildCapacity": 55,
    "guildMember": 40
  },
  "petInfo": {
    "id": 1300000113,
    "level": 4,
    "exp": 540,
    "isSelected": true,
    "skinId": 1310000132,
    "selectedSkillId": 1315000014
  },
  "socialInfo": {
    "language": "Language_English",
    "signature": "Don't Look At My Profile Just Watch My Gameplay",
    "preferMode": "Prefermode_CS"
  },
  "creditScoreInfo": {
    "creditScore": 100
  }
}
```
