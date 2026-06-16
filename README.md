# Releases

Binary releases for [SuperInference AMI](https://www.superinference.org).

Built by CI on every push to `main`.
The install script always fetches the latest release:

```bash
curl -fsSL https://www.superinference.org/install.sh | bash
```

Binaries: `ami-cli-linux-x64`, `ami-cli-darwin-arm64`, `ami-cli-windows-x64.exe`

VS Code extension is automatically packaged in a .vsix and published directly in the
[Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=superinference.ami-vscode).
