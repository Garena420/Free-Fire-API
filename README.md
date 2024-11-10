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
{ "AccountInfo": { "AccountId": "7802788212", "AccountType": 1, "AccountName": "ㅤㅤᎫᎧᗫㅤㅤ?", "AccountRegion": "IND", "AccountLevel": 57, "AccountEXP": 674160, "AccountAvatarId": 901041005, "AccountBannerId": 902000052, "BrRankPoint": 2352, "AccountBPBadges": 24, "AccountBPID": 1001000078, "AccountSeasonId": 42, "AccountLikes": 13259, "AccountLastLogin": 1731227598, "CsRankPoint": 130, "EquippedWeapon": [ 907193503 ], "BrMaxRank": 213, "CsMaxRank": 221, "AccountCreateTime": 1685272409, "Title": 904590054, "ReleaseVersion": "OB46", "ShowBrRank": true, "ShowCsRank": true }, "AccountProfileInfo": { "EquippedOutfit": [ 205000225, 211000435, 211000927, 203043019, 204000343, 214000023 ], "EquippedSkills": [ 16, 706, 8, 1, 16, 1306, 8, 2, 16, 3406, 8, 3, 16, 6906 ] }, "GuildInfo": { "GuildID": "67744100", "GuildName": "PGㅤEMP1RE", "GuildOwner": 972431060, "GuildLevel": 6, "GuildCapacity": 55, "GuildMember": 40 }, "petInfo": { "id": 1300000113, "level": 4, "exp": 540, "isSelected": true, "skinId": 1310000132, "selectedSkillId": 1315000014 }, "socialinfo": { "AccountLanguage": "Language_English", "AccountSignature": "Don't Look At My Profile Just Watch My Gameplay", "AccountPreferMode": "Prefermode_CS" }, "creditScoreInfo": { "creditScore": 100 } }
```
