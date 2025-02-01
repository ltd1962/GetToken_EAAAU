# GetToken_EAAAU

### 1. How to use - Cách sử dụng

```
# Method POST: "https://ltdsoftware.online/api/ltdsoftware/tokeneaaaau.php"
# Form-Data:
# uid: 61572548613514
# pass: Ashim@29
# fa2: A66YSRJOBRCRYX54J32JPWPTSLRQHAUO
```

### 2. Result - Kết quả trả về
# Success - Thành công
```
Example - Ví dụ
{
    {
    "session_key": "5.fTB17MuxA_H4Wg.1738406631.19-61572548613514",
    "uid": 61572548613514,
    "secret": "b6ee0595b4bbbb0a6ce925d38a8303ee",
    "access_token": "EAAAAUaZA8jlABOypQKi3xoUxMZBDne2DuS9GGzcZAvLfHJL8GZAcc0nuekgQLBpgdR2CWRZAJ2ZA8B6I0YZBwJvCpL6cRTy255JDz0yVNg684MlQpoVaYmjSOserS20TsbeRePz0X4KzxQeOHRV7IjdsuPxiGZCMdPszqIy1UooORwaTs8L3ATYhI4BK0ngTJCiY3rg0wvt70wZDZD",
    "machine_id": "5_qdZySftCLTXCv6Zrtj97e7",
    "session_cookies": [
        {
            "name": "c_user",
            "value": "61572548613514",
            "expires": "Sun, 01 Feb 2026 10:43:51 GMT",
            "expires_timestamp": 1769942631,
            "domain": ".facebook.com",
            "path": "/",
            "secure": true,
            "samesite": "None"
        },
        {
            "name": "xs",
            "value": "19:fTB17MuxA_H4Wg:2:1738406631:-1:-1",
            "expires": "Sun, 01 Feb 2026 10:43:51 GMT",
            "expires_timestamp": 1769942631,
            "domain": ".facebook.com",
            "path": "/",
            "secure": true,
            "httponly": true,
            "samesite": "None"
        },
        {
            "name": "fr",
            "value": "0ObZJrEYvHyweUqRI.AWXCEU-mCddnsTtbsbxqmG8BImqtMDkAmMF4YQ.Bnnfrn..AAA.0.0.Bnnfrn.AWUEiNWYoug",
            "expires": "Fri, 02 May 2025 10:43:51 GMT",
            "expires_timestamp": 1746182631,
            "domain": ".facebook.com",
            "path": "/",
            "secure": true,
            "httponly": true,
            "samesite": "None"
        },
        {
            "name": "datr",
            "value": "5_qdZySftCLTXCv6Zrtj97e7",
            "expires": "Sun, 08 Mar 2026 10:43:51 GMT",
            "expires_timestamp": 1772966631,
            "domain": ".facebook.com",
            "path": "/",
            "secure": true,
            "httponly": true,
            "samesite": "None"
        }
    ],
    "analytics_claim": "hmac.AR10BnFi0efduLmwBKCZLlYTd7KPDlj5k65LvJiqCVOjJ9JI",
    "confirmed": true,
    "user_storage_key": "6c2600e321bfb3f43b22efa3292006daaaad6ef1239f80357889e9ec8cd10485",
    "is_account_confirmed": true,
    "is_msplit_account": false,
    "is_fb_only_not_allowed_in_msgr": false,
    "is_marketplace_consented": true,
    "is_gaming_consented": true
}
}
```

# Fail - Thất bại
```
Example - Ví dụ
{
    ""
}
```
