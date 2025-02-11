### User profile Base64
Right-click anywhere on a profile and open 'View Source Code', then search for 'UserID'. Enter the USERID into the format below and convert to base64

```
{"rp_author":"{\"name\":\"author\",\"args\":\"[USERID]\"}"}
```

**Base64 Encoder**
```
https://codebeautify.org/base64-encode
```

**Base64 Decoder**
```
https://codebeautify.org/base64-decode
```

Example of using the output to search:

```
https://facebook.com/search/posts/?q=posts&epa=FILTERS&filters=[ENTER BASE64]
```