# secure-auth-examples

Educational C++ examples demonstrating secure authentication patterns — **for learning only**.  
This repo contains a local sandbox (no real accounts) showing password hashing (Argon2), TOTP 2FA, HTTPS demo, and common pitfalls with fixes.

**Important:** Do not use any code here in production without review. This project is intended for education and testing in a local environment only.

## Contents
- examples/simple_login_demo — console login with Argon2 hashed passwords
- examples/totp_demo — TOTP generator & verifier (RFC6238)
- examples/https_server_example — simple HTTPS server (Boost.Beast + OpenSSL)
- docs/ARCHITECTURE.md, SECURITY.md, CONTRIBUTING.md
