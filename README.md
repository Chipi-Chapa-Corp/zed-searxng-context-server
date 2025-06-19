# Zed Sear Context Server

This extension provides a Model Context Server for SearXNG, for use with the Zed AI assistant.

It adds a `/search` slash command to the Assistant Panel.

## Configuration

To use the extension, you will need to point the context server at a SearXNG instance by setting the `api_url` in your Zed `settings.json`:

```json
{
  "context_servers": {
    "searxng-context-server": {
      "settings": {
        "api_url": "http://127.0.0.1:8088"
      }
    }
  }
}
```

## Usage

- `/search <query>`: Search web for the given query.
