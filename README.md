# Isle Save Tools

A utility for encrypting and decrypting Isle save files.

## Basic Commands

Encrypt a JSON file:
```
islesave encrypt path/to/save.json
```

Decrypt a save file:
```
islesave decrypt path/to/save.sav
```

## Batch Processing

Process multiple files at once:
```
islesave batch encrypt path/to/directory --pattern "*.json"
islesave batch decrypt path/to/directory --pattern "*.sav"
```

## Requirements

- Python 3.10+
