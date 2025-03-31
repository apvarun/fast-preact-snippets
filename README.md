# Fast Preact Snippets: VS Code Snippets

Streamline Preact development with this focused collection of VS Code snippets.

## Features:

* Essential Preact snippets for rapid development.
* Optimized for the latest Preact version.
* Common patterns and components for efficient coding.

## Snippets

| Snippet | Renders                                       |
| ------- | --------------------------------------------- |
| `imp`   | Import Preact h function                      |
| `impc`  | Import Preact, { Component }                  |
| `imph`  | Import Preact with hooks                      |
| `imps`  | Import Preact with useState hook              |
| `impse` | Import Preact with useState and useEffect     |
| `impr`  | Import Preact/compat for React compatibility  |
| `cc`    | Class Component                               |
| `ccc`   | Class Component With Constructor              |
| `fc`    | Functional Component                          |
| `nfc`   | Named Functional Component                    |
| `fsc`   | Function Syntax Component                     |
| `cdm`   | componentDidMount                             |
| `uef`   | useEffect Hook                                |
| `ucb`   | useCallback Hook                              |
| `scu`   | shouldComponentUpdate                         |
| `cdu`   | componentDidUpdate                            |
| `cwun`  | componentWillUnmount                          |
| `ss`    | setState                                      |
| `ssf`   | Functional setState                           |
| `usf`   | Declare a new state variable using State Hook |
| `usr`   | Declare a new ref variable using Ref Hook     |
| `ren`   | render                                        |
| `cp`    | Context Provider                              |
| `cpf`   | Class Property Function                       |
| `efsc`  | Function Syntax Component Inline              |

## Full Expansions

### imp - Import Preact h function

```javascript
import { h } from 'preact';
```

### impc - Import Preact, Component

```javascript
import { h, Component } from 'preact';
```

### imph - Import Preact with hooks

```javascript
import { h } from 'preact';
import { useState, useEffect } from 'preact/hooks';
```

### imps - Import Preact with useState hook

```javascript
import { h } from 'preact';
import { useState } from 'preact/hooks';
```

### impse - Import Preact with useState and useEffect hooks

```javascript
import { h } from 'preact';
import { useState, useEffect } from 'preact/hooks';
```

### impr - Import Preact/compat for React compatibility

```javascript
import { createElement } from 'preact/compat';
```

## License

MIT