# Racket Web Server

## Why? 

Just in case reproducing (functionally) the C server fails, here is another that should be a drag and drop replacement.

## Dependencies
- racket
- the racket library rfc6455.
``` bash
raco pkg install rfc6455
```
## Running
```bash
racket main.rkt
```
Runs a WebSockets server on port 9010 by default. Messages are echoed from connected clients to the Unity app.
