# Minzip
A compression library for small strings.

## Todo
- tests
- get library working
- document usage (and add example usage)
  - ensure that examples show up nicely on pub.dev
- collect stats on compression ratio
- CI via github actions

## Developing
To fetch dependancies, run:
```
pub get
```

To build, run:
```
pub run build_runner build
```

To test, run:
```
pub run build_runner test
```

To publish new version:
```
# make sure to update CHANGELOG.md first
pub publish --dry-run
```

## References
- https://github.com/antirez/smaz
- http://ed-von-schleck.github.io/shoco/
- https://github.com/gtoubassi/femtozip

