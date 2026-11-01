# vroom

Static GitHub Pages site served at [vroom.czix.in](https://vroom.czix.in).

It hosts the Tesla Fleet API public key at:

https://vroom.czix.in/.well-known/appspecific/com.tesla.3p.public-key.pem

The public key is committed at `.well-known/appspecific/com.tesla.3p.public-key.pem`.

The private key must never be committed. `.gitignore` ignores `*private*.pem` and `private-key.pem`.
