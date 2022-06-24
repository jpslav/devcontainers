# devcontainers

Install a VS Code devcontainer setup in your current directory.

Here's an example:

```bash
$> curl -s https://raw.githubusercontent.com/jpslav/devcontainers/main/run | bash /dev/stdin --type typescript1 --name "My Service" --docker-base node:16.14
```

Or running simply with `--help` will give you the options, and also print out the temp directory to which the tool was installed if you'd like to run it directly:

```bash
$> curl -s https://raw.githubusercontent.com/jpslav/devcontainers/main/run | bash /dev/stdin --help
```

Gives...

```bash
Cloning the devcontainers tool to a temporary directory: /var/folders/blah/blah/devcontainer-XXXXXXXXXX.AzEoDRYg
Installing the devcontainer files with /var/folders/blah/blah/devcontainer-XXXXXXXXXX.AzEoDRYg/install --help
Creates a VS Code devcontainer configuration in the current directory
  -n, --name=<s>           Devcontainer name
  -t, --type=<s>           Kind of devcontainer environment, one of [typescript1]
  -c, --color=<s>          Editor color to differentiate the app (optional, hex format without the pound sign)
  -d, --docker-base=<s>    Docker base image
  -h, --help               Show this message
```

