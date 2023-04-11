# Desktop init scripts

## Setup OS

### Setup Ubuntu

```text
curl -fsSL https://raw.githubusercontent.com/agoloncser/desktop-init-scripts/master/src/00_ubuntu.sh | sh -xv
```

### Setup macOS

```text
curl -fsSL https://raw.githubusercontent.com/agoloncser/desktop-init-scripts/master/src/00_mac.sh | sh -xv
```

### Setup Fedora

```text
curl -fsSL https://raw.githubusercontent.com/agoloncser/desktop-init-scripts/master/src/00_fedora.sh | sh -xv
```

## Misc init scripts

### Trust Github ssh hostkeys

```text
curl -fsSL https://raw.githubusercontent.com/agoloncser/desktop-init-scripts/readme/src/03_trust_github.sh | sh -xv 
```

### Caps-lock to control on Gnome

```text
curl -fsSL https://raw.githubusercontent.com/agoloncser/desktop-init-scripts/master/src/99_caps.sh | sh -xv
```

### Generate host ssh key

```text
curl -fsSL https://raw.githubusercontent.com/agoloncser/desktop-init-scripts/master/src/02_genssh.sh | sh -xv
```

### Setup GnuPG

```text
curl -fsSL https://raw.githubusercontent.com/agoloncser/desktop-init-scripts/master/src/01_gpg.sh | sh -xv
```