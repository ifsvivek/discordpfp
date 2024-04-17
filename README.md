# Discord PFP

## To add new PFP

```css
[src^="https://cdn.discordapp.com/avatars/<UID>"]
{
  content: url(<IMG-LINK>);
  object-fit: scale-down;
  aspect-ratio: 1;
}
```

## To add new BG

```json
{"_id":"6153e41189d9b9e27d9650??","uid":"<UID>","img":"<IMG-LINK>","orientation":"none"},
```

**Remember to change last 2 char in \_id with proper chars**

## To add to your Discord

```css
@import url("https://raw.githubusercontent.com/ifsvivek/discordpfp/main/main.css");
```
