# Vibetype
A typing test...
...except it's completely done by AI.

## How to use
### In your current directory
```sh
curl -o vibetype https://raw.githubusercontent.com/lunaflight/vibetype/refs/heads/main/vibetype && chmod +x vibetype
```
```sh
./vibetype --help
```

### System-wide access
```sh
curl -o /usr/local/bin/vibetype https://raw.githubusercontent.com/lunaflight/vibetype/refs/heads/main/vibetype && sudo chmod +x /usr/local/bin/vibetype
```
```sh
vibetype --help
```

## Developing
Only use [Gemini](https://gemini.google.com) and prompt it to hell.

Then just keep blindly doing `xclip -out -sel clip > vibetype` to accept changes.

65 prompts have been used. AI is coming for my job :)
