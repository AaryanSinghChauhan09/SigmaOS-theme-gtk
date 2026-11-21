# SigmaOS-theme-gtk

SigmaOS integration component for **GTK3 theme settings**.

## Commands

```bash
sigmaos-theme-gtk install   # install package + deploy defaults
sigmaos-theme-gtk deploy    # copy config templates to $HOME
sigmaos-theme-gtk status    # binary/package/config report
sigmaos-theme-gtk reset     # remove deployed config
sigmaos-theme-gtk open      # launch the application
```

## Design

- Shell-based component manager (Omarchy-style per-app repos)
- Secure defaults; no secrets stored
- Deterministic `test.sh` with isolated `$HOME`
