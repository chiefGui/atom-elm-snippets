# Elm snippets for Atom

Adding some shortcut sugar to your day-by-day programming in Elm on Atom.

_Disclaimer: this package is in early stage. I'm not covering all the possible scenarios, but the most ones used by me. Feel free to PR!_

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
