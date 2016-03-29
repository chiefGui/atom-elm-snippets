# Elm snippets for Atom

Adding shortcuts to your day-by-day programming in Elm on Atom.

_Disclaimer: this package is in early stage. I'm not covering all cases as possible, but the most ones by me. Feel free to PR!_

### Install

`apm install elm-snippets`

### Snippets

Write the prefixes below and press the `Tab` key and you're good to go.

#### [mod]

```elm
module <name> (..) where
```

#### [imp]

```elm
import <name>
```

#### [impas]

```elm
import <name> as <alias>
```

#### [impea]

```elm
import <name> exposing (..)
```

#### [ta]

```elm
type alias <name> =
  <something>
```

#### [str]

```elm
String
```

#### [sig]

```elm
Signal
```

#### [sigma]

```elm
Signal.map <(a -> b)> <Signal a>
```

#### [sigmb]

```elm
Signal.mailbox ""
```

#### [cof]

```elm
case <something> of
  <Condition> ->
    <action>
```
