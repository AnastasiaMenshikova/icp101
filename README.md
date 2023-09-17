# ICP smart contract example

This is example of project on the Internet Computer Protocol (ICP) platform using TypeScript. [Source](https://dacade.org/communities/icp)

[How to setup and interact with Smart Contracts on the Internet Computer](https://dacade.org/communities/icp/courses/typescript-smart-contract-101/learning-modules/b14741ea-ee33-43a4-a742-9cdc0a6f0d1c)

There is no native support for `dfx` on Windows. However, by installing the Windows Subsystem for Linux (WSL), you can run `dfx` also on a Windows system.
[Installing the IC SDK](https://internetcomputer.org/docs/current/developer-docs/setup/install/) | [Install Linux on Windows with WSL](https://learn.microsoft.com/en-us/windows/wsl/install)

Once you have WSL installed, you can install `dfx` by running:

```bash
sh -ci "$(curl -fsSL https://internetcomputer.org/install.sh)"
```

Next, run `dfx start --background`. Then run `dfx deploy`.
