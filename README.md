
Simple static HTML app.

Just do this:

```bash
oc apply -k overlays/s2i
```

Or this:

```bash
oc new-app --context-dir=app nginx~https://github.com/dlbewley/static.git
oc expose service/static
```
