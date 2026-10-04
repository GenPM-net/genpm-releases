# genpm releases

Native `genpm` binaries (macOS, Linux, Windows). Source code: [genpm.net](https://genpm.net).

Install:

```bash
curl -fsSL https://genpm.net/install.sh | sh
```

```powershell
irm https://genpm.net/install.ps1 | iex
```

The installer picks your platform, verifies the binary against `SHA256SUMS` and installs it in `~/.genpm/bin`. Update with `genpm upgrade`.
