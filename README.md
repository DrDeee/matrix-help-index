# matrix-help-index
This repo contains the help messages for *@bot4future:fff.chat*, the matrix bot of FridaysForFuture Germany.
These messages are used by [this](https://github.com/drdeee/maubot-help) [Maubot](https://github.com/maubot/maubot) plugin.

## Structure
### `commands.json`
This file contains all commands with the corresponding messages:`
```json
{
  "command": "help message here, with optional markdown formattings"
}
```

### `categories.json`
This file contains all categories, as well as all included commands.
```json
{
  "category display name 1": [
    "command1",
    "command2",
    "..."
  ],
  "category display name 2": [
    "command3",
    "command4",
    "..."
  ]
```
All commands that are not assigned to a category are automatically assigned to the default category, which can be defined in the plugin's config.
