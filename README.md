# rl-test

Runs `rl test` on `.rl` files. Fails the job on test failure.

```yaml
- uses: rl-lang/rl-test@main
  with:
    file: tests.rl      # or folder: tests/
    match: money         # optional --match filter
```

| Input | Default |
|---|---|
| `version` | `latest` |
| `file` | `''` |
| `folder` | `''` |
| `match` | `''` |
| `args` | `''` |
| `working-directory` | `.` |

One of `file` or `folder` is required.
