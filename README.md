# asdf-maven

[Maven](https://en.wikipedia.org/wiki/Apache_Maven)
plugin for the [asdf](https://github.com/asdf-vm/asdf) version manager.

## Forked
This repository was forked because it had 2 (known) issues I came across.

For more information:
[Illegal sed -s option for Mac](https://github.com/skotchpine/asdf-maven/issues/15)
[JAVA_HOME not found](https://github.com/skotchpine/asdf-maven/issues/22)

## Install

After installing [asdf](https://github.com/asdf-vm/asdf),
you can add this plugin like this:

```bash
asdf plugin-add maven https://github.com/Hacklor/asdf-maven.git
```

and install new versions like this:

```bash
asdf install maven 3.5.4
```

and switch versions like this:

```bash
asdf global maven 3.5.4
```

## Reading

Read the [asdf readme](https://github.com/asdf-vm/asdf)
for instructions on how to install and manage versions of any language.

If you have trouble with any expected features,
have any feature requests or want to contribute,
please [do an issue](https://github.com/skotchpine/asdf-maven/issues).

## Development

- asdf's [creating-plugins.md](https://github.com/asdf-vm/asdf/blob/master/docs/creating-plugins.md)
- [Bash Hackers Wiki](http://wiki.bash-hackers.org/)
