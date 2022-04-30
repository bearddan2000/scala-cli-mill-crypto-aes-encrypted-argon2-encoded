# scala-cli-mill-crypto-aes-encrypted-argon2-encoded

## Description
Encrypt and decrypt password with AES
encoded with argon2.

When storing a password it is best practice
to use a one-way hash such as bcrypt, scrypt,
or argon2.

## Tech stack
- scala
- mill
  - aes
  - argon2

## Docker stack
- nightscape/scala-mill

## To run
`sudo ./install.sh -u`

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
