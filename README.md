# Last Update
**Date: 07 dec**

# 📝 API Documentation

# 🪪 Account Information
**Endpoint:** `/player_info`  
**Method:** `GET`  
**Description**
This endpoint retrieves account information based on the specified region and user ID.

### ☑️ Query Parameters

| Parameter | Type   | Required | Description                   |
|-----------|--------|----------|-------------------------------|
| `uid`     | string | Yes      | The user ID.
| `region`  | string | Yes      | The region code (`IND`, `BR`, `SG`, `RU`, `ID`, `TW`, `US`, `VN`, `TH`, `ME`, `PK`, `CIS`, `BD`).
| `key`     | string | Yes      | Your Key.|
### 📨 Request Example
```http
GET https://garena420ffapi.vercel.app/profile_info?uid={uid}&region={region}&key={key}
```


### 💬 Response Example
```json
{
  "AccountInfo": {
    "AccountAvatarId": 902000052,
    "AccountBPBadges": 26,
    "AccountBPID": 1001000079,
    "AccountBannerId": 901041005,
    "AccountCreateTime": 1685272409,
    "AccountEXP": 694739,
    "AccountLastLogin": 1733481508,
    "AccountLevel": 57,
    "AccountLikes": 15427,
    "AccountName": "ㅤㅤᎫᎧᗫㅤㅤ?",
    "AccountRegion": "IND",
    "AccountSeasonId": 42,
    "AccountType": 1,
    "BrMaxRank": 220,
    "BrRankPoint": 3598,
    "CsMaxRank": 219,
    "CsRankPoint": 99,
    "EquippedWeapon": [907193503],
    "ReleaseVersion": "OB47",
    "ShowBrRank": true,
    "ShowCsRank": true,
    "Title": 904290048
  },
  "AccountProfileInfo": {
    "EquippedOutfit": [205000225, 211000435, 211000927, 203043019, 204000343, 214000023],
    "EquippedSkills": [16, 706, 8, 1, 16, 1806, 8, 2, 16, 6906, 8, 3, 16, 5806]
  },
  "GuildInfo": {
    "GuildCapacity": 25,
    "GuildID": "3037521443",
    "GuildLevel": 2,
    "GuildMember": 13,
    "GuildName": "Pђσєиɪχ",
    "GuildOwner": "7802788212"
  },
  "captainBasicInfo": {
    "EquippedWeapon": [907193503],
    "accountId": "7802788212",
    "accountType": 1,
    "badgeCnt": 26,
    "badgeId": "1001000079",
    "bannerId": "901041005",
    "createAt": "1685272409",
    "csMaxRank": 219,
    "csRank": 219,
    "csRankingPoints": 99,
    "exp": 694739,
    "headPic": "902000052",
    "lastLoginAt": "1733481508",
    "level": 57,
    "liked": 15427,
    "maxRank": 220,
    "nickname": "ㅤㅤᎫᎧᗫㅤㅤ?",
    "pinId": "910035002",
    "rank": 220,
    "rankingPoints": 3598,
    "region": "IND",
    "releaseVersion": "OB47",
    "seasonId": 42,
    "showBrRank": true,
    "showCsRank": true,
    "title": 904290048
  },
  "creditScoreInfo": {
    "creditScore": 100,
    "periodicSummaryEndTime": "1733616987",
    "periodicSummaryStartTime": "1733357787"
  },
  "petInfo": {
    "exp": 540,
    "id": 1300000113,
    "isSelected": true,
    "level": 4,
    "selectedSkillId": 1315000002,
    "skinId": 1310000132
  },
  "socialinfo": {
    "AccountLanguage": "Language_English",
    "AccountPreferMode": "Prefermode_BR",
    "AccountSignature": "[b][c][00FF00] Telegram: Garena420"
  }
}
```
