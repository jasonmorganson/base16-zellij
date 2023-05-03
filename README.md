# base16-zellij

A [base16](https://github.com/chriskempson/base16) template for [Zellij](https://zellij.dev/), a user friendly terminal muxer.

To use:

* Build a config file using your builder of choice (I use [flavours](https://github.com/Misterio77/flavours))
* Put it in `~/.config/zellig/themes/default.kdl`

Restart zellij.

Here's my flavours config, just in case someone needs it:

```toml
[[items]]
file = "~/.config/zellij/themes/default.kdl"
template = "zellij"
subtemplate = "default"
rewrite = true
```
