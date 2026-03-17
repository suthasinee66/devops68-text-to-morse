# Text to Morse Code API

Convert text to Morse code.

## Endpoint

### GET `/convert`

**Parameters:**
- `text` (required): Text to convert to Morse code

**Example Request:**
```
http://localhost:3030/convert?text=hello
```

**Example Response:**
```json
{
  "input": "hello",
  "morse": ".... . .-.. .-.. ---"
}
```
