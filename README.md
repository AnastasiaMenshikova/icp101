There is no native support for `dfx` on Windows. However, by installing the Windows Subsystem for Linux (WSL), you can run `dfx` also on a Windows system.
[Installing the IC SDK](https://internetcomputer.org/docs/current/developer-docs/setup/install/) | [Install Linux on Windows with WSL](https://learn.microsoft.com/en-us/windows/wsl/install)

Once you have WSL installed, you can install `dfx` by running:

```bash
sh -ci "$(curl -fsSL https://internetcomputer.org/install.sh)"
```

Next, run `dfx start --background`. Then run `dfx deploy`.
