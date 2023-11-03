# cmp-emoji

nvim-cmp source for emojis.

This fork includes a fix for the issue [that emoji suggestions are not triggered
after quote characters](https://github.com/hrsh7th/cmp-emoji/issues/2).
Otherwise, it is identical to `hrsh7th/cmp-emoji`.

# Setup

```lua
require'cmp'.setup {
  sources = {
    { name = 'emoji' }
  }
}
```

# Option

#### insert (type: boolean)

Speficy emoji should be insert or not.

Default: `false`

