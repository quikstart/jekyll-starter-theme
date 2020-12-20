# Jekyll Quick Starter Template / Scaffold - Build Your Own (Gem-Packaged) Theme

Use like:

```
$ quik new jekyll-theme
```

This will download and run
the quik starter wizard script ([`quik.rb`](quik.rb)). Resulting in:

```
Hello from the jekyll theme quick starter wizard script

Q: Name of the theme? [hola]: hola

Thanks! Ready-to-go. Stand back.

  Downloading Jekyll Theme Starter Template...
  Setting up Jekyll Theme Starter Template...
  ...
  Merging templates...
    name:   "hola"
    ...
Done.
```

Resulting in:

```
hola
├───assets/
│   └── .keep
├───_includes/
│   └── .keep
├───_layouts/
│   ├── default.html
│   ├── page.html
│   └── post.html
├───_sass/
│   └── .keep
│   .gitignore
│   Gemfile
│   hola.gemspec
│   LICENSE.txt
└── README.md

```

That's it.


## More (Alternative) Quick Starter Templates / Scripts

See the [Quik Scripts](https://github.com/quikstart/scripts) catalog / directory or try:

```
$ quik ls
```

to list all "official" registered quick starter templates / scripts.


## Questions? Comments?

Send them along to the ruby-talk mailing list.
Thanks!



---

## TODOs

Use git settings for user.name and user.email e.g.

in `$filename$.gemspec`:

```
  spec.authors       = ["Otto Maximal"]
  spec.email         = ["otto.maximal@example.com"]
```

### Dev Notes

For now $name$ and $filename$ is the same e.g. hola == hola etc.
