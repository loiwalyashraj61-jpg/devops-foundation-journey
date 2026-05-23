# DNS Basics 🌐

## What is DNS?

DNS (Domain Name System) converts human-readable domain names into IP addresses.

Example:

google.com → 142.250.x.x

Because computers communicate using IP addresses, not domain names.

---

## Real World Analogy

DNS works like a phone contact list.

You remember:
"Google"

But your phone internally stores:
Phone Number

Similarly:

Human remembers:
google.com

Internet uses:
IP Address

---

## Basic Flow

User enters:
google.com

↓
DNS Resolver checks IP

↓
IP address returned

↓
Browser connects to server

---

## Why DNS is Important

Without DNS, users would need to remember IP addresses for every website.

Example:
Instead of:
google.com

You would type:
142.250.x.x

---

## Practical Command

```bash
nslookup google.com
```

This command helps check DNS resolution.

---

## Learning Goal

Understanding DNS is important for:
- Networking
- DevOps
- Cloud

- Server communication
- Production debugging
