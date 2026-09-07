# DalamudPlugins

Distribution container and shared custom repository for my FFXIV Dalamud plugins.

## Install

In Dalamud, open `/xlsettings`, go to **Experimental → Custom Plugin Repositories**, and add:

```text
https://raw.githubusercontent.com/link-0402/DalamudPlugins/main/repo.json
```

After saving, the plugins listed in [`repo.json`](repo.json) appear in `/xlplugins`.

## Adding a plugin

`repo.json` is a JSON array. Add one complete object per plugin. Each plugin must have a unique `InternalName`, and its download links must point to a uniquely named archive on that plugin's GitHub Releases page:

```text
https://github.com/<owner>/<plugin-repository>/releases/latest/download/<unique-asset-name>.zip
```

This repository contains only the shared index and documentation. Plugin source code and release workflows remain in their individual repositories.

## Included plugins

| Plugin | Source |
| --- | --- |
| [WindowResize+](https://github.com/link-0402/WindowResizePlus) | [link-0402/WindowResizePlus](https://github.com/link-0402/WindowResizePlus) |
