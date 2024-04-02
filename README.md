# mx5repo

## Introduction

Personal gentoo portage overlay.

### Using repositories (eselect)

```Bash
eselect repository add mx5repo git https://github.com/meredith620/mx5repo.git
```

### manual configuration
1. Clone repo into local path
```
git clone https://github.com/meredith620/mx5repo.git
```

1. Register the overlay

```Bash
[mx5repo]
location = /<OVERLAY_ROOT_TO>/mx5repo
sync-type = git
sync-uri = https://github.com/meredith620/mx5repo.git
auto-sync = true
```

