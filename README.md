# Add Project by Path

Codex++ tweak that adds a native-looking **Enter project path** action to the Codex project menu.

It lets you add a project without opening the system folder picker:

- paste a local path, `file://` URL, or shell command like `cd /path && ...`
- drag and drop a folder onto the modal
- automatically create the target folder when it does not exist
- get precise validation errors for permissions, files, relative paths, and broken paths

## Install

Copy this folder into your Codex++ tweaks directory:

```sh
~/Library/Application\ Support/codex-plusplus/tweaks/co.sakushi.add-project-by-path
```

Codex++ hot reloads tweaks on save. If it does not appear immediately, force reload or restart Codex.
