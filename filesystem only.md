//this can be used for desktop claude when using filesystem to keep the output of execution in local system
// as document or screenshot after using claude

//claude_desktop_config.json

{
  "mcpServers": {
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