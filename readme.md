# HYPERPATRIKBOMBERTEXTMESSAGEPROTOCOL (HPBTMP)

## requests
### a request is sent like: REQ#\<client\>::\<reqtype\>$\<arg1\>$\<arg2\>$etc
## responses
### a response is sent like: RES#\<client\>::\<responsetype\>@\<satuscode\>$\<args\>
## status messages (used when indicating something like going to toilet)
### a status ius sent like: STA#\<client\>::\<statuscode\>$\<args\>

## special requests
### REQ::PING - pings the remote for status.

# valid status codes
## 2xx
200 - passed (or available when responding to ping)
## 4xx
404 - brain has not been able to find the requested thing
## 5xx
500 - brain error<br>
501 - BUSY (general)<br>
502 - BUSY (doing something with someoone else)<br>
503 - BUSY (resolving some issue like spilled water
## 6xx
600 - going to toilet<br>
601 - going to drink<br>
602 - going to play with pet
