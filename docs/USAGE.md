# WiFi Duck — Usage

## A harmless first payload

Paste this in the web UI and run it on your **own** Windows machine — it just opens
Notepad and types a line.

```text
REM wifi_duck_hello - safe demo
DELAY 1000
GUI r
DELAY 300
STRING notepad
ENTER
DELAY 600
STRING Quack. Sent over WiFi.
```

> Authorized testing and education only. See docs/SAFETY.md.

