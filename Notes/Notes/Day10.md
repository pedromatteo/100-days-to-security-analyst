# Burp Suite Fundamentals

## Proxy

Browser
↓
Proxy (Burp)
↓
Server

---

## HTTP Flow

Browser

↓

Request

↓

Server

↓

Response

↓

Browser

---

## Request

Contains:

- Method
- URL
- Headers
- Body (optional)

---

## Response

Contains:

- Status Code
- Headers
- Body

---

## Common HTTP Methods

GET
Retrieve data.

POST
Send data.

---

## Burp Proxy

Intercept ON

Request stops.

↓

Analyze

↓

Modify

↓

Forward

↓

Server

---

## Important

Burp does **not** generate network packets.

The browser creates the request.

Burp intercepts, displays, modifies (if desired), and forwards it.