# CAVRI

CAVRI stands for content-addressable, verifiable, and resilient internet.

## Layer 0 (CA)

Content-addressable. Addressing immutable data using cryptographic hashes. For example:
  - `ni://sha256:879e1aa6bce969d0624d1b769664ef723d2df871cf68b4c338d101b282b9d482/somefile.txt`

## Layer 1 (V)

Verifiable. DID and [self]-verifiable content (digital signatures). It can be used to address mutable data. For example:
  - `did://secp256k1:4hqwkd52rv0nmz71a4vnmg0ry0kjczmw6czgcz2xv755z407fzja/my-project/some.json`

Both layers are protocol agnostic and allow the building of RI (resilient internet).
