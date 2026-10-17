# coreyervin/scoop-bucket

[Scoop](https://scoop.sh) manifests for my tools.

```powershell
scoop bucket add coreyervin https://github.com/coreyervin/scoop-bucket
```

## yolk

Keeps your PC awake and Slack and Teams active while AI agents run, so a long
loop doesn't die when the machine falls asleep.

```powershell
scoop install yolk
```

Installs the tray app, with a **Yolk** shortcut in the Start menu, and puts the
`yolk` CLI on your `PATH`. Needs Windows 10 or later.

See [coreyervin/yolk](https://github.com/coreyervin/yolk).

## Maintenance

- **Update** checks for a new yolk release every six hours and commits the new
  version and hash. Run it by hand to pick up a release straight away.
- **Test** installs each manifest with real Scoop on Windows on every push.
