# ktfmt

This is a VS Code extension for running [ktfmt] as a Kotlin formatter.

It does not contain `ktfmt`. You should install the JAR into some path and then
tell this extension where to look via the `ktfmt.path-to-jar` to set the path.
If you do not have `JAVA_HOME` set properly you may also need to set
`ktfmt.java_home`. Once that is done you need to set it as your default
formatter for kotlin files by adding to your config,

```json
{
  "[kotlin]": {
    "editor.defaultFormatter": "crdrost.ktfmt"
  }
}
```

## Known Issues

Nothing right now.

## Release Notes

[ktfmt]: https://github.com/facebookincubator/ktfmt
