//this can be used for desktop claude when using playwright with filesystem to keep the output of execution in local system
// as document or screenshot

//claude_desktop_config.json

{
  "mcpServers": {
    "playwright": {
      "command": "npx",
      "args": [
        "@playwright/mcp@latest"
      ]
    }
    ,
    "filesystem": {
        "command": "npx",
        "args": [
            "-y",
            "@modelcontextprotocol/server-filesystem",
            "/Users/yourpcusername/Desktop"
        ]
        }
    }
}