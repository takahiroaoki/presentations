# presentations

My presentations slides repository using [Slidev](https://ja.sli.dev/).

## how to use

### setup

```
$ mise i
$ npm ci
```

### start presentation

```
$ mise run slides ${material name}
```

###  export as pdf

```
$ mise run export ${material name}
```

## rules

### directory structure

Presentation materials should be stored as the following.

```
./materials
└ ${material name}
    └ slides.md
    └ assets/ # image files, etc.
    └ drafts/ # concepts, drafts, etc.
```

### prepare new presentation

Please copy `./materials/_template` directory for a new presentation.

```
$ mise run new ${material name}
```
