# Kanagawa

## Semantic tokens

Theme supports and recommends enabling semantic tokens.

### TypeScript

Enabled by default.

### Go

```json
{
  "gopls.ui.semanticTokens": true
}
```

#### rust-analyzer

```json
{
  "rust-analyzer.highlighting.strings": true
}
```

#### `C#`

```json
{
  "csharp.semanticHighlighting.enabled": true
}
```

## Customization

### Comments

If you prefer comments to stand out in your code - this looks nice:

```json
{
  "editor.tokenColorCustomizations": {
    "[Kanagawa]": {
      "comments": {
        "foreground": "#FF9E3B"
      }
    }
  }
}
```

Paste it in your `settings.json`.

## Misc

You can find this theme's colors for different terminal emulators [here](https://github.com/rebelot/kanagawa.nvim#extras).
If you like this theme, consider supporting [original author](https://github.com/rebelot/kanagawa.nvim#donate).
