# cabled

[english](./Readme.md)
[한국어](./Readme.ko.md)

Cabled is a development pattern that makes user input and their action well separated so modularized, and making **Undo** and **Replay** easier.

## Structure

Regular programs are designed like this:

```
Input -> Action (Directly)
```

Scalable cabled pattern-designed:

```
Input as cabled.Input (Queued) -> Action dispatcher -> Action
```

## Implementation

WIP
