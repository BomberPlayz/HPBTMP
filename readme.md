# HYPERPATRIKBOMBERTEXTMESSAGEPROTOCOL (HPBTMP)

## requests
### a request is sent like: REQ::<reqtype>$<arg1>$<arg2>$etc
## responses
### a response is sent like: RES::<responsetype>@<satuscode>$<args>
## status messages (used when indicating something like going to toilet)
### a status ius sent like: STA::<statuscode>$<args>

## special requests
### REQ::PING - pings the remote for status.

# valid status codes
## 2xx
### 200 - passed (or available when responding to ping)
## 4xx
### 404 - brain has not been able to find the requested thing
## 5xx
### 500 - brain error
### 501 - BUSY (general)
### 502 - BUSY (doing something with someoone else)
### 503 - BUSY (resolving some issue like spilled water
## 6xx
### 600 - going to toilet
### 601 - going to drink
### 602 - going to play with pet
