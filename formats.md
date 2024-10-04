# Block Formats

## Directory

```json
{
  "directory": {
    "filename.txt": "hash1",
    "a/b/c.md": "hash2"
  }
}
```

## Revision

```json
{
  "revision": {
    "current": "hash1",
    "previous": ["hash2", "hash3"]
  }
}
```

## Digital Signature

## TimeStamp

## Aliases

They can be used as human-readable path and as branches. 

```json
{
  "aliases": {
    "alias1": "hash1",
    "alias2": "public_key1",
    "alias3": "public_key2/alias",
  }
}
```

## Contacts

```
{
  "contacts": {
    "public_key": [
      "tel:555-555-5555", "mailto:example@example.com", "https://example.com", "birthday:date"
    ],
  }
}
```
