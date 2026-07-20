# Day 12 Notes

## Python HTTP Server Architecture

Client

↓

Browser

↓

GET /

↓

HTTPServer

↓

BaseHTTPRequestHandler

↓

do_GET()

↓

Open index.html

↓

HTTP 200 OK

↓

Content-Type

↓

HTML Response

---

## Important Concepts

### send_response()

Generates:

HTTP/1.0 200 OK

---

### send_header()

Adds HTTP Headers.

Example:

Content-Type: text/html

---

### end_headers()

Marks the end of the HTTP headers.

Everything sent after this belongs to the HTTP Body.

---

### wfile.write()

Sends the HTML file to the browser.

---

### self.path

Stores the requested resource.

Examples:

/

/login

/favicon.ico

/admin

---

### with open()

Opens a file and automatically closes it after use.

---

### Binary Mode

rb

r = Read

b = Binary