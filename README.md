#### pshttp2funda

- 7
Establishing an h2c connection:
(TLS + ALPN) application layer protocal negotiation

-8
some settings:
```
SETTINGS_HEADER_TABLE_SIZE
SETTINGS_ENABLE_PUSH
SETTINGS_MAX_CONCUEERNT_STREAMS
SETTINGS_INITIAL_WINDOW_SIZE
SETTINGS_MAX_FRAME_SIZE
SETTINGS_MAX_HEADER_LIST_SIZE
```

-9
header fields:
etag = 123ABCDEF
host = domain.com
content-length = 128

pseudo fields:
:method = POST
:path = /
host
content-length

Request:
```
:method
:scheme
:authority
:path
```
Response
```
:status
```
