# customized-base64
base64 encoding encode binary data to string for sending the binary data over string-formated network.
You can test [base64 encoding](https://www.base64decode.org/) and [base64 decoding](https://www.base64encode.org/)
The table used in base64 encoding can be shown in [base64 wiki](https://en.wikipedia.org/wiki/Base64)

Customized base64 encoding uses little modified table as below.
All of others except the table are same with base64 encoding.

## Encoding table

| 6-bits value | converted string |
|---|---|
| 0~25 | a~z |
| 26~51 | A~Z |
| 52~61 | 0~9 |
| 62 | + |
| 63 | / |
