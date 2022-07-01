# Yours Canary

## What is a canary?

Once per month, we will publish a canary in the form of a cryptographically signed message containing the following:

- A declaration that, up to that point, no warrants or subpoenas have been served, nor have any searches or seizures taken place.
- Headlines from major news sources demonstrating that the update could not have been created prior to that date.

Special note should be taken if these messages ever cease being updated, or are removed from this page. However this scheme is not infallible.  Although signing the declaration makes it impossible for a third party to produce arbitrary declarations, it does not prevent them from using force to coerce us to produce false declarations.

All canaries created will be kept in this repository.

# How to verify a canary?

These canaries are signed with a PGP key.

To verify the signatures using GnuPG:

1. Download the public key file.
2. gpg --import public.key
3. Download the latest canary.
4. gpg --verify canary.txt

You should see a message similar to below confirming the signature is good:

```
gpg: Signature made Thu Jun 30 23:28:35 2022 EDT
gpg:                using RSA key 55D75B9F47712B014C947B039CF7845EC1782E02
gpg: Good signature from "Brian Lee"
```
