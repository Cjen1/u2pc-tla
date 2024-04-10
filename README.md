# Unanimous 2PC

TLA+ check using
```
tlc U2PC_MC.tla -deadlock -simulate -workers auto
```

Apalache check using
```
apalache-mc simulate --cinit=CInit --inv=Invs --length=100 U2PC_MC.tla
```
