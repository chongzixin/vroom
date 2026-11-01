# vroom

Static GitHub Pages site served at [vroom.czix.in](https://vroom.czix.in).

It hosts the Tesla Fleet API public key at:

https://vroom.czix.in/.well-known/appspecific/com.tesla.3p.public-key.pem

Add the real public key at `.well-known/appspecific/com.tesla.3p.public-key.pem`. Do not commit a placeholder key.

The private key must never be committed. `.gitignore` ignores `*private*.pem` and `private-key.pem`.
