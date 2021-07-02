```
cabal configure -v3
```

```
[_13] trying: C:B:exe.A~>A-0.1.0.0 (dependency of C:B:exe.B)
[_14] rejecting: C:B:exe.A:!test (dependencies not linked: stanza "test" incompatible; conflict set: A, B, C:B:exe.A, C:B:exe.B, A:test, C:B:exe.A:test)
```
